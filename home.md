---
title: Overview
description: 
published: true
date: 2020-11-03T02:46:33.179Z
tags: 
editor: markdown
dateCreated: 2020-10-05T03:30:34.427Z
---

# Welcome to SciFi Farm's (SFF) Wiki

# Overview
This wiki is the place to store anything related to SciFi Farms (SFF) or TechnoCore. It's very much a work in progress and colaboration(THIS SHOULD BE A LINK) is encoraged. Below are the main components you'll likely be interested in. 

## Major Components
- **Working with TechnoCore**
TechnoCore is a framework for deploying various Docker services into a Swarm cluster. It's the platform that SFF built and uses to manage our software services and SeedShips.
- **Working with SeedShips**
Fundamentially, SeedShips are CEA (Controlled Environment Agrculture) environments that rely heavily on open source and IoT (Internet of Things) technologies that have been modified and preconfigured to work together and scale with ease. 
- **Developing TechnoCore**
How to get a functional development enviornment as well as the assumptions that must be satisfied in order for things to happen automagically. 
- **Contributing** 
For a long time, I was unable to support contributors because the architeture and services were changing so frequently, but that has changed and this documentation is written with the hope that others will read it and have something to add. 
- **Controlled Environment Agriculture** (Not yet started)
Notes and resources for what you might need to run your own controlled enviornment. 
- **SciFi Farm**
Information and notes on the business side of SciFi Farms

### Core Services:
Funamentially, TechnoCore is designed to run other services. Here is documentation for the ones that are currently utilized: 
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
It is a stack of open source services to be used in running a SciFi Farm. It 

It's deployed and managed using TechnoCore to make installation/deployment easy and envs from development to production consistent. 


## What is TechnoCore?
It takes multiple repos with a specific layout and uses that to generate and combine docker-compose.yaml files that ultimately get deployed to a Docker Swarm. 

Currently, it's primary purpose is to create and manage SciFi Farm instances, but it can do more than that; for example, this wiki is being ran by TechnoCore!




The methods of configuration from Docker images vary greatly and don't usually 

Docker services don't share a standard way to do configuration and initilization, so TechnoCore services contains a number of pre-implemented solutions and workarounds for commonly found anti-patterns. 


## What is a SeedShip?
A SeedShip is a growing environment managed by a SciFi Farm instance.  

