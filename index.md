---
layout: default
title: Home
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

## Meeting Minutes

<ul>
  {% for minute in site.minutes %}
    <li>
      <a href="{{ minute.url | relative_url  }}">{{ minute.title }}</a>
    </li>
  {% endfor %}
</ul>


## Slack Channel

The S-RCWG Slack channel can be found [here](https://swc-neuro.slack.com/archives/C01CK2NTV32)

## Proposal Template

Use this template to compose a new proposal as a pull request on [our GitHub]({{site.url}}):

- <a href="proposal_template.html">A Template for New Proposals</a>
