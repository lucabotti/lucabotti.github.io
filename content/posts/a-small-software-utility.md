---
title: "A small Software Utility"
slug: a-small-software-utility
summary:
date: 2025-03-02T00:27:35+01:00
publishDate: 2025-03-03
tags: [python,vault]
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

# A small sofware utility

A recent Database update on a set of microservices, requiring multiple updates to the connection string, made me search for a solution to search and replace values inside [Hashicorp Vault](https://www.vaultproject.io/).

I was unable to make a go project that i found work for my use case, and as such I assembled a quick solution in Python. After having used it extensively for a couple of months, I am releasing it as a free software (MIT Licensed) on GitHub, as [vault-search-replace](https://github.com/RedSoftwareSystems/vault-search-replace) If you need it, it's there.

I will publish it on PyPI as well (it works as a script). And ideally I will refine it in the next months, adding Python development best practices.

This is the kind of value that the [Delivering Value]({{< ref "delivering-value" >}}) post was talking about - you give value to your users.

In this example, the value is for me, first, potentially others, second.

Enjoy!





