# Roadmap
This document defines a high level roadmap for Yorkie development and upcoming releases.
The features and themes included in each milestone are optimistic in the sense that many do not have clear owners yet.
Community and contributor involvement is vital for successfully implementing all desired items for each release.
We hope that the items listed below will inspire further engagement from the community to keep Yorkie progressing and shipping exciting and valuable features.

Any dates listed below and the specific issues that will ship in a given milestone are subject to change but should give a general idea of what we are planning.
We use the [Projects](https://github.com/orgs/yorkie-team/projects) feature in Github so look there for the most up-to-date and issue plan.

## Yorkie v0.1

Yorkie's first release version, v0.1, aims to implement the basic features of the document store for building collaborative editing applications. And it should be reliably available for services used in production environments.

### 2019
 - Nov: Start the project with adding basic structure(Agent, Client, Document)
 - Dec: JS-SDK(Client, Document) [yorkie-js-sdk](https://github.com/yorkie-team/yorkie-js-sdk)

### 2020
 - Jan: Text datatype for supporting text based collaboration editor [#2](https://github.com/yorkie-team/yorkie/issues/2)
 - Feb: Realtime event stream API [#5](https://github.com/yorkie-team/yorkie/issues/5)
 - Mar: https://yorkie.dev [yorkie-team.github.io](https://github.com/yorkie-team/yorkie-team.github.io)
 - Apr: Change hook
 - May: Snapshot API to reduce payload [#9](https://github.com/yorkie-team/yorkie/issues/9)
 - Jun: Garbage collection to clean CRDT meta [#3](https://github.com/yorkie-team/yorkie/issues/3)
 - Aug:
   - Peer Awareness [#48](https://github.com/yorkie-team/yorkie/issues/48)
   - Introducing Prometheus metrics [#76](https://github.com/yorkie-team/yorkie/issues/76)
 - Sep: Supporting TLS and Auth webhook to secure Yorkie [#6](https://github.com/yorkie-team/yorkie/issues/6)
 - Nov: Introducing HA [#11](https://github.com/yorkie-team/yorkie/issues/11)
 - Dec: Redo/Undo API [#49](https://github.com/yorkie-team/yorkie/issues/49)

## Yorkie v0.2

### 2021
 - Jan: Speed up push/pull changes and snapshot
