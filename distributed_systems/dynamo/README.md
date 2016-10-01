# Dynamo: Amazon's Highly Available Key-value Store

For CMPS232 Fall16

- [Dynamo: Amazon's Highly Avaliable Key-value Store](http://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)

Related to TBD

## Short summary

see [summary.md](summary.md)

Strong points

- The introduction shows the structure of each section.
- 99.9 percentile for customer experience, engineers' relentless focus
- 'Give services control over their system properties, let services make their own tradeoffs', like Waldo's paper, engineers need to know what they are doing, don't try to unify everything.

Weak points

- The first paragraph in introduction is verbose. 'to support continuous growth the platform needs to be highly scalable', 'to support continuous growth, the platform needs to be highly scalable'
- TBD
- TBD

Questions

- what is `application state` mentioned in introduction
- what is consisting hashing
- what is ... see the supplemental part, idk all of them
- sec 2. Each service that uses Dynamo runs its own Dynamo instances.
- sec 2.3 P2 how to detect replica conflicts, the paper only mentioned about how to resolve?


## Supplemental

- synthesis: combination
- [ ] consistent hashing
- [ ] object versioning
- [ ] quorum-like
- [ ] gossip based ?
- expected variance https://www.dartmouth.edu/~chance/teaching_aids/books_articles/probability_book/Chapter6.pdf
- provisioning https://en.wikipedia.org/wiki/Provisioning
- heterogeneity, difference, 多相性
## Ref