---
layout: default
title: index
---

# Science Research Culture Working Group Portal

## Proposals

<ul>
  {% for proposal in site.proposals %}
    <li>
      <a href="{{ proposal.url | relative_url  }}">{{ proposal.title }}</a> ({{ proposal.authors }}) <em>{{ proposal.excerpt }} </em>
    </li>
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

