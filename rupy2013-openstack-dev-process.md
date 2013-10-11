---
title: "RuPy 2013: on OpenStack Development: How we build it, and how you can help"
date: 2013-10-11 15:00 EST
tags:
 - events
---

You can read a more detailed log at [teropa.info](http://teropa.info). My review is more a 

[Cody from HP works on OpenStack](https://twitter.com/somerville32)

He explained how HP works with automation and collaboration on their vast teams.

## Gerrit for code review

Code review is a responsibility - needing +2 from other developers - that probably means using Gerrit, right?

git-review: a command-line tool to open the right Gerrit page.

Here, the process at HP is like the one a friend described that Spotify uses.

**Tools criticize mechanically-measurable things**, such as code style. Leaves **humans to criticize the ideas**.

## QA

Automated QA: unit tests, integration tests, smoke tests.

In order to learn from crashes, **they process logs aggressively**: ElasticSearch, logstash. In order to search the history of problem-solving, they classify parts of the log.

They communicate a lot. EtherPad! IRC! MLs! Dev Summit! That summit has 4K humans in one place - Hong Kong. Where do all those come from? (I missed the bar chart.)

## Audience participation: low

Questions from the audience are tame to non-existent: are these developers that far removed from ops? From development process? From agility? I do not know.





