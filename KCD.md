### 1. KubeAid: Stop Rebuilding the Same Kubernetes Stack for Every New Cluster

Setting up a production Kubernetes cluster means weeks configuring monitoring, GitOps, secrets management, and backups. Then you need another cluster and start over. This is one of the biggest time sinks for SRE teams. KubeAid is an open-source toolkit that solves this problem with production ready configurations for monitoring, GitOps, secrets, disaster recovery, and more - all managed through Git.

In this presentation, I will introduce KubeAid and the problem it solves, walkthrough how it provisions clusters across different platforms (AWS, Azure, Hetzner, bare metal). I will then demonstrate a live cluster setup. Later I will explain KubeAid's architecture, and share real-world use cases and success stories from companies using it in production. I will also discuss our unique open-source sustainability model. The session will conclude with a QnA to address questions from the attendees.


### 2. Day-2 Kubernetes: Where Most Production Clusters Break - and How KubeAid Fixes It

Provisioning a Kubernetes cluster is only the beginning. Most production incidents don’t happen on day one - they happen on day two and beyond, when monitoring alerts don’t fire, secrets need rotation, backups fail silently, upgrades introduce breaking changes, and clusters slowly drift out of control.

This talk will focus on the real challenges of Kubernetes day-2 operations drawing directly from experience building and operating KubeAid in real environments by KubeAid Creators, we will walk through the most common operational pain points SRE and platform teams face after clusters go live.

Using KubeAid we’ll explore how day-2 concerns such as monitoring, GitOps, secrets management, backups, and disaster recovery can be standardized and managed entirely through Git. We will talk about how KubeAid applies opinionated, production-tested defaults to reduce operational overhead. Throughout the session, we’ll share practical operational tips and lessons learned from creating and maintaining KubeAid - what worked, what failed, and what actually matters when running Kubernetes in production. The session will conclude with a QnA to discuss questions from the audience.
