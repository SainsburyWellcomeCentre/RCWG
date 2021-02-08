---
layout: default
title: RCWG
---

# Science Research Culture Working Group Portal

*We are a group of SWC and GCNU people thinking and acting to improve our research environment and practices*.

## Proposals

### Active 

<ul>
{% for proposal in site.proposals %}
{% if proposal.category == "active" %}
      <li>
        <a href="{{ proposal.url | relative_url  }}">{{ proposal.title }}</a> ({{ proposal.authors }})
        <em>{{ proposal.excerpt }} </em>
      </li>
{% endif %}
{% endfor %}
</ul>

### Suggested

<ul>
{% for proposal in site.proposals %}
{% if proposal.category == "suggested" %}
      <li>
        <a href="{{ proposal.url | relative_url  }}">{{ proposal.title }}</a> ({{ proposal.authors }})
        <em>{{ proposal.excerpt }} </em>
      </li>
{% endif %}
{% endfor %}
</ul>

### Completed

<ul>
{% for proposal in site.proposals %}
{% if proposal.category == "completed" %}
      <li>
        <a href="{{ proposal.url | relative_url  }}">{{ proposal.title }}</a> ({{ proposal.authors }})
        <em>{{ proposal.excerpt }} </em>
      </li>
{% endif %}
{% endfor %}
</ul>

## Minutes

<ul>
  {% for minute in site.minutes %}
  <li>
    <a href="{{ minute.url | relative_url  }}">{{ minute.title }}</a>
  </li>
  {% endfor %}
</ul>


## Slack

The S-RCWG Slack channel can be found [here](https://swc-neuro.slack.com/archives/C01CK2NTV32)

## GitHub

You can submit proposals and minutes on [our GitHub](https://github.com/SainsburyWellcomeCentre/S-RCWG)

<br>
<br>
