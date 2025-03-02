---
title: "The Chaotic Architect"
slug: the-chaotic-architect
summary:
date: 2024-11-22T11:04:51+01:00
image: chaotic-architect.png
publishDate:
tags: [software,architecture]
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

# The Chaotic Architect

**Disclaimer:**_this is the original version of the LinkedIn post at https://www.linkedin.com/pulse/chaotic-architect-red-software-systems-bsuaf_

## Part 1 - Introduction
We often think to software architecture as clear, plain vision of the components of a system or software solutions. A clear-cut, CAD like vision of a Cathedral that a team of software engineers will build with the precision of ancient craftmanship, driven by the wise suggestions of team leaders, with the cadence of a ballet orchestrated by Project Managers.

Indeed, the sad truth is that software architecture often grows from chaotic, not well-defined requirements, and from the improvised ideas of mid level developers who try to use the latest and the greatest of the suggestions in the software industry, without really thinking to the business needs underlying the project or product in development.

Just to think to the latest trends, is the complexity of distributed transactions in a microservice architecture balanced by the scaling needs of our software solution? Or are we trying to infinitely scale a tailored business application which will serve not more than 300 people as a whole? Benefits of containerization are clear, but do we need a custom self-managed Kubernetes cluster, or some Ansible based virtual machines will suffice for our customers? 

Citing Eric Raymond, although out of context, software development is more often similar to a bazaar, with requirements and needs fluidly changing all the time, and architecture should willingly and knowingly continuously adapt to these changes. Instead, more often than not, architects come to think of themselves more like archistars, bringing the light and the truth (the Real Light and the Real Truth, of course...) and trying to fit the software in the architecture, not the other way around. 

Last but not least, software architectures are more or less cyclical, and you can draw parallels between the current wave of proposed solutions and past ones: 

 * SPAs resemble the good old client/server paradigm, with modern technologies in server and the client side (web frontend, APIs), but also some of the same issues(state management ?) 
 * gRPC is CORBA all the way back - without the broker 
 * Kubernetes system abstraction is a return to mainframe (also the headcount needs resemble it)

Jokes aside, once you have been in the industry for some time (yours truly is counting about 32 years...) you can start to have a sense of deja-vu in relations to the architecture, and detach from the proposal du jour. 

So this is my way of thinking the architecture - a somewhat chaotic approach to solve solutions, ready to change and adapt to the needs that arise, not the ones that **MAY** arise.

Additionally, we must be aware of bias. Over time, everyone develops preferences in relation to solutions, languages, frameworks, and the proposed architecture  naturally drifts in the direction of the bias, even unwillingly. 

This is why this post is named "The Chaotic Architect" - the real challenge in software development and architecture is being prepared to change and chaos management.








