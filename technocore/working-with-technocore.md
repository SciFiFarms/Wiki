---
title: Working With TechnoCore
description: 
published: true
date: 2020-11-03T02:59:00.345Z
tags: 
editor: markdown
dateCreated: 2020-11-03T02:46:02.003Z
---

## What is TechnoCore?
TechnoCore takes multiple git repos with a specific layout and uses them to generate and combine docker-compose.yaml files that ultimately get deployed to a Docker Swarm. 

More than that, docker services don't share a standard way to do configuration and initilization, so TechnoCore services contains a number of pre-implemented solutions and workarounds for commonly found anti-patterns. 

Currently, it's primary purpose is to create and manage SciFi Farm instances, but it can do more than that; for example, this wiki is being ran by TechnoCore!

