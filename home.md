---
title: Untitled Page
description: 
published: true
date: 2020-10-21T03:41:57.130Z
tags: 
editor: markdown
dateCreated: 2020-10-05T03:30:34.427Z
---

# Overview
This wiki is intened to be the place to store anything related to SciFi Farms or TechnoCore. 

## What is a SciFi Farm? 
It is an approach to running a farm that relies heavily on automating the various components of a farm as well as collects and presents the various sensor readings. 

## What is the SciFi Farm Stack? 
It is a stack of open source services to be used in running a SciFi Farm. It relies heavily on open source and IoT (Internet of Things) technologies that have been modified and preconfigured to work together. It's deployed and managed using TechnoCore to make installation/deployment easy and envs from development to production consistent. 

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


## What is TechnoCore?
TechnoCore is a framework for deploying various Docker services into a Swarm cluster. It takes multiple repos with a specific layout and uses that to generate and combine docker-compose.yaml files that ultimately get deployed to a Docker Swarm. The methods of configuration from Docker images vary greatly and don't usually share a standard way to configure and initilize, so TechnoCore tries to take a standarized approach and has solutions for commonly found anti-patterns. Currently, it's primary purpose is to create and manage SciFi Farm instances, but it can do more than that; for example, this wiki is being ran by TechnoCore!


## What is a SeedShip?
A SeedShip is a growing environment ran by a SciFi Farm. Presently the main growing condition 


Your content here
![image.png](/image.png)
```diagram
PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB2ZXJzaW9uPSIxLjEiIHdpZHRoPSIyNDFweCIgaGVpZ2h0PSI4MXB4IiB2aWV3Qm94PSItMC41IC0wLjUgMjQxIDgxIiBjb250ZW50PSImbHQ7bXhmaWxlIGhvc3Q9JnF1b3Q7ZW1iZWQuZGlhZ3JhbXMubmV0JnF1b3Q7IG1vZGlmaWVkPSZxdW90OzIwMjAtMTAtMDVUMDM6MjA6MTEuMjA5WiZxdW90OyBhZ2VudD0mcXVvdDs1LjAgKFgxMSkmcXVvdDsgdmVyc2lvbj0mcXVvdDsxMy43LjcmcXVvdDsgZXRhZz0mcXVvdDs2aXppRjJHeS1EWWRPSk1NRmwycCZxdW90OyB0eXBlPSZxdW90O2VtYmVkJnF1b3Q7Jmd0OyZsdDtkaWFncmFtIGlkPSZxdW90O0ZUb0ZOSFNjSXdxV2lXVDg3amhvJnF1b3Q7IG5hbWU9JnF1b3Q7UGFnZS0xJnF1b3Q7Jmd0O3JaVEJVb013RUlhZmhxc0R4RHFlYmFzZTlOU0Rlc3lRTGNRSkxCT1dBajY5b1d3S0ROWTZZMC9OZnZtejJmMjdJUkRydkgyeXNzeGVVWUVKNGxDMWdkZ0VjUnhGcTlqOTlLUWJ5TDBJQjVCYXJWZzBncDMrQW9aZVZtc0YxVXhJaUlaME9ZY0pGZ1VrTkdQU1dtem1zajJhK2EybFRHRUJkb2swUy9xbUZXWGN4U29jK1RQb05QTTNSeUh2NU5LTEdWU1pWTmhNa05nR1ltMFJhVmpsN1JwTWI1NzNaVGozZUdiM1ZKaUZndjV5NEpiTG9NNzNCc3ExeWlGYXlqREZRcHJ0U0I4czFvV0NQa0hvb2xIemdsZzZHRG40Q1VRZC8yK3lKblFvbzl6d0xyU2EzaWZyano3VnpZcWpUY3VaajBISHdWQm5YOXpaVGhsVldOdUVWVHhuSkcwS3JCSW5sOTE0QXVaQXRuTVNDMGFTUHN5elM1NlQ5S1FiclhRTGR2Tm5aL25xZ3pRMUoxMVkzV1NhWUZmS1k3V05leXB6bTJSVkRzTzcxMjF2TjN0d0FFdlEvdTdDc2o5L3dNOG92N3pUSURhVE9XYVVUVWJZcy84NElpNDc0cDVEMlM5YnRLN2ZDLzVjd1E0aEx0dHhkeDA3WERnKzYrUGU1T01vdHQ4PSZsdDsvZGlhZ3JhbSZndDsmbHQ7L214ZmlsZSZndDsiPjxkZWZzLz48Zz48cGF0aCBkPSJNIDgwIDQwIEwgMTczLjYzIDQwIiBmaWxsPSJub25lIiBzdHJva2U9IiMwMDAwMDAiIHN0cm9rZS1taXRlcmxpbWl0PSIxMCIgcG9pbnRlci1ldmVudHM9InN0cm9rZSIvPjxwYXRoIGQ9Ik0gMTc4Ljg4IDQwIEwgMTcxLjg4IDQzLjUgTCAxNzMuNjMgNDAgTCAxNzEuODggMzYuNSBaIiBmaWxsPSIjMDAwMDAwIiBzdHJva2U9IiMwMDAwMDAiIHN0cm9rZS1taXRlcmxpbWl0PSIxMCIgcG9pbnRlci1ldmVudHM9ImFsbCIvPjxyZWN0IHg9IjAiIHk9IjAiIHdpZHRoPSI4MCIgaGVpZ2h0PSI4MCIgZmlsbD0iI2ZmZmZmZiIgc3Ryb2tlPSIjMDAwMDAwIiBwb2ludGVyLWV2ZW50cz0iYWxsIi8+PHBhdGggZD0iTSAxODAgMCBRIDI0MCAwIDI0MCA0MCBRIDI0MCA4MCAxODAgODAgUSAyMTAgNDAgMTgwIDAgWiIgZmlsbD0iI2ZmZmZmZiIgc3Ryb2tlPSIjMDAwMDAwIiBzdHJva2UtbWl0ZXJsaW1pdD0iMTAiIHBvaW50ZXItZXZlbnRzPSJhbGwiLz48L2c+PC9zdmc+
```
![2020-07-30-163021.webm](/2020-07-30-163021.webm)

[2020-07-30-163021.webm](/2020-07-30-163021.webm)