---
title: Overview
description: 
published: true
date: 2020-11-03T02:03:02.391Z
tags: 
editor: markdown
dateCreated: 2020-10-05T03:30:34.427Z
---

# Welcome to SciFi Farm's Wiki

# Overview
This wiki is the place to store anything related to SciFi Farms or TechnoCore. It's very much a work in progress and colaboration(THIS SHOULD BE A LINK) is encoraged. Below are the main components you'll likely be interested in. If you're unsure, 

### Core Services:
- ESPHome
- Grafana
- VerneMQ
- Home Assistant
- InfluxDB
- Traefik 
- Hashicorps Vault
- SMTP Relay

### Supporting Services:
- Syncthing
- Jupyter Notebooks
- Node Red


## What is a SciFi Farm? 
It is an approach to running a farm that relies heavily on automating the various components of a farm as well as collects and presents the various sensor readings. 

## What is the SciFi Farm Stack? 
It is a stack of open source services to be used in running a SciFi Farm. It relies heavily on open source and IoT (Internet of Things) technologies that have been modified and preconfigured to work together. It's deployed and managed using TechnoCore to make installation/deployment easy and envs from development to production consistent. 


## What is TechnoCore?
TechnoCore is a framework for deploying various Docker services into a Swarm cluster. It takes multiple repos with a specific layout and uses that to generate and combine docker-compose.yaml files that ultimately get deployed to a Docker Swarm. The methods of configuration from Docker images vary greatly and don't usually share a standard way to configure and initilize, so TechnoCore tries to take a standarized approach and has solutions for commonly found anti-patterns. Currently, it's primary purpose is to create and manage SciFi Farm instances, but it can do more than that; for example, this wiki is being ran by TechnoCore!


## What is a SeedShip?
A SeedShip is a growing environment managed by a SciFi Farm instance.  

