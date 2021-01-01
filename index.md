---
layout: default
title: Home
---

# Science Research Culture Working Group Portal

<!-- - [Weekly data and/or non-data clubs](proposals/weeklyDataNonDataClubs.html)
> The goal of this proposal is to generate a culture of consistent internal scientific communication within the building.
- [Cross-disciplinary rotations](proposals/rotations.html)
<blockquote>The goal of this proposal is to generate a culture of consistent internal scientific communication within the building.</blockquote>
- [Collaborative data clubs](proposals/collaborativeDataClubs.html)
- [Journal clubs deliverd by experimental and computational neuroscientists](proposals/jcsByComputationalAndExperimental.md)
- [Talks by external leaders of collaborative research](proposals/talksByLeaderssInCollaborativeResearch.md)
- [Yearly internal symposiums](proposals/yearlyInternalSymposiums.md)
- [Seed grants for collaborative research](proposals/seedGrants.html)
- [(Certified) training in open-science tools](proposals/trainingInOpenScience.html)
- [Science slack channels](https://swc-neuro.slack.com/files/T7S8UFBGR/F01GBDU8EMN) (Slack link)
- [Science working groups](proposals/scienceWorkingGroups.html)
- [Open-science forum](proposals/openScienceForum.html)
 -->

## Proposals

<ul>
  {% for proposal in site.proposals %}
    <li>
      <a href="{{ proposal.url }}">{{ proposal.title }}</a> ({{ proposal.authors }}) <em>{{ proposal.excerpt }} </em>
    </li>
  {% endfor %}
</ul>

## Meeting Minutes

<ul>
  {% for minute in site.minutes %}
    <li>
      <a href="{{ minute.url }}">{{ minute.title }}</a>
    </li>
  {% endfor %}
</ul>


## Slack Channel

The S-RCWG Slack channel can be found [here](https://swc-neuro.slack.com/archives/C01CK2NTV32)

## Proposal Template

Use this template to compose a new proposal as a pull request on [our GitHub]({{site.url}}):

- <a href="proposal_template.html">A Template for New Proposals</a>
