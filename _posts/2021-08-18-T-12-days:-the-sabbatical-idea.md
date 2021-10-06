---
layout: post-with-before-and-after-links
title:  "T-12 Days: The Sabbatical Proposal"
date:   2021-08-18 11:27:24 -0400
categories: jekyll update
---

✨ Blog post number 1! Woooo!

👩‍💻 I have been at VMware (and Pivotal before it was acquired) for over 5 years,
which means I am able to apply for a 3 month "sabbatical". Usually people work
on other teams that they are interested in, but I decided to spend my 3 months
becoming a golang contributor.

📄 Below is the proposal I put together to convince my leadership that it was a
good use of time.

> ### Contributing to Golang Open Source
>
> During my sabbatical I want to become a golang open source contributor and gain a deeper
understanding of networking in golang. This will enable me to better support our
customers when TAS has problems where golang is the root cause.
>
> **Why this is relevant**
>
> I am an engineer on the Cloud Foundry Networking Team. I have been building
and maintaining networking and routing components written in golang for 3.5
years, including: cf-networking-release, silk-release, and routing-release.
>
> Things regularly come up that require looking deeper into how golang implements
its networking stack. Some examples:
* [Why is Expect 100-continue causing problems with a golang reverse
  proxy?](https://www.cloudfoundry.org/blog/cve-2020-15586/)
* [Why do some invalid HTTP responses cause golang reverse proxy to
  fail?](https://www.cloudfoundry.org/blog/cve-2020-5420/)
* [Why do headers from certain Java apps cause golang reverse proxies to
  fail?](https://community.pivotal.io/s/article/Application-Chunked-Error?language=en_US)
* [Why does golang not allow certain ciphers for TLS1.3 that the RFC says are
  allowed?](https://github.com/golang/go/issues/29349)
* [How can we alter the golang reverse proxy to allow us to pass through
  encrypted h2c traffic?](https://github.com/golang/go/issues/45786)
>
> For all of those examples I was involved in digging through the golang code to
determine the root cause of an issue.
>
> I have gotten better at poking around in the code, but I want to be able to
contribute to it. I don’t want to be forced to wait months until they look at
our issue. When these big issues come up, I want to be able to submit a PR to
golang to help solve our customer’s issues.
>
> **Quantitatively Measurable Outcomes**
* Submit PRs with docs changes
* Submit PRs with bug fixes
* Be involved in discussion on issues
* Build a professional network in the golang community
>
> **Qualitatively Measurable Outcomes**
* Become more comfortable debugging golang
* Gain a deeper understanding of networking with golang
* Gain the ability to easily submit PRs to golang in the future
* Become more active in the golang community


🍀 So that's the idea! Wish me luck!
