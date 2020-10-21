---
title: Development with TechnoCore
description: 
published: true
date: 2020-10-21T04:07:43.039Z
tags: 
editor: markdown
dateCreated: 2020-10-21T04:07:43.039Z
---

# How to develop with Technocore
    
- PROD
- repo-template
- compose.yml
- defaults.sh
- secrets.sh
- Migrations & dogfish
- Goinit and entrypoints
- Docker images - auto built & updated
- init.sh
- VS Code workspace
- Troubleshooting

<SERVICE_NAME> should match the folder name in services/.

## Commands
- build 
- clean
- generate_getmodules

## How to add a service to TechnoCore
1. Create new repo from [template](https://github.com/SciFiFarms/TechnoCore-Template)
2. Clone new repo `git clone <YOUR REPO URL HERE> repo_name_without_technocore`
3. In compose.yml, replace EXAMPLE_SERVICE with your service name (lower case). I use vim and `%s:/EXAMPLE_SERVICE/<SERVICE_NAME>/g`.
4. There are a couple of notes about uppercasing variables. Where noted, change to uppercase. 
5. Go through compose.yml and make any changes I know are needed. 
6. Integrate any known docker-compose.yaml values. 
7. Either delete Dockerfile.template or rename to Dockerfile and edit as needed. This should mostly be uncommenting features that are desired.
8. Build image if needed
9. Add service to .env file and `./tc deploy`
10. Test, fix, rebuild, redeploy as needed until the service configuration & code is ready to be committed.
11. Commits done along the way should be pushed here. 
12. Add line for new repo in TechnoCore/technocore.stack.sh
13. Setup Docker Hub build. Eventually should be worked into a more selfhosted CI/CD solution.

