---
title: "Real Problems Real Solutions"
slug: real-problems-real-solutions
summary:
date: 2024-12-12T00:27:35+01:00
publishDate: 2024-12-12
tags: 
  - python
  - github
  - bitbucket
series: 
toc: false
draft: false
---
<!--
Checklist:
- [ ] Outline
- [ ] Draft 1
- [ ] Edit
    - [ ] Check trouble / vale
    - [ ] One sentence per line
    - [ ] Check preview in browser
    - [ ] Put in all links
- [ ] Create summary
- [ ] Tidy up
    - [ ] Set publishDate
    - [ ] Toggle draft
    - [ ] Check tags
    - [ ] Remove checklist
    - [ ] Remove outline
- [ ] Publish to hosting

Outline:
- 
-->
At [RED Software Systems](https://red.software.systems) we recently switched from the Atlassian Suite to GitHub.

Considerations for doing so come down mostly to price and the complexity of the suite and the overlapping of some tools with others.

We highly value Jira, and BitBucket as a service is second to none. But the complexity of the tooling - Jira - is astounding, and gets in the way for the kind of relatively small projects we follow.

Even a small company like us has accumulated around 300 private repositories in the past ten years, so a manual migration through the web interface is out of discussion.

Enter [Repository Migrate](https://github.com/RedSoftwareSystems/repository-migrate), a simple script to migrate all of the organization repositories from BitBucket to GitHub (and the other way around).

Obviously, before writing the script (which is very simple), I searched for an already made solution (which I couldn't find), so started writing the script which I am also releasing as a PyPI package.

The script has a set of commands, which have been defined only by the **_real problems_** encountered while migrating our repositories.

This is the kind of value that the [Delivering Value]({{< ref "delivering-value" >}}) post was talking about - you give value to your users.

In this instance, us.





