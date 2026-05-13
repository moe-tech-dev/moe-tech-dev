# Moe

I like the unglamorous part of software: getting small services online, making
them observable, and leaving enough notes that the next fix does not depend on
memory.

I work mostly around Linux servers, web hosting, small dashboards, and developer
tools. The goal is simple: build things that are useful, inspectable, and not
mysterious after deployment.

## What I Build

- small status and service dashboards for real infrastructure
- static websites that are easy to deploy and hand off
- Linux runbooks with the commands, tradeoffs, and recovery notes included
- tiny CLI tools for answering practical machine and environment questions
- reproducible patch notes instead of vague "fixed it locally" history

## Selected Projects

| Project | What it is | Why it matters |
| --- | --- | --- |
| [service-watch-dashboard](https://github.com/alsharmani0/service-watch-dashboard) | A browser dashboard for checking HTTP service health. | Turns "is it down?" into a quick answer instead of a terminal hunt. |
| [website-atelier-heimw](https://github.com/alsharmani0/website-atelier-heimw) | A real public website for a local art atelier. | Plain HTML/CSS, deployed simply, with the actual site at [atelier-heimw.de](https://atelier-heimw.de). |
| [homelab-mini](https://github.com/alsharmani0/homelab-mini) | A small Ubuntu/Rocky Linux homelab setup. | Documents reverse proxy, SSH hardening, firewall rules, and SELinux without pretending the lab is bigger than it is. |
| [sysinfo-cli](https://github.com/alsharmani0/sysinfo-cli) | A Python CLI for system information. | Gives quick CPU, memory, disk, and OS output as text or JSON. |
| [openclaw-upstream-patches](https://github.com/alsharmani0/openclaw-upstream-patches) | Sanitized patch notes and issue context. | Keeps upstream-fix work reproducible instead of trapped in a local checkout. |

## Current Bet

I am turning `service-watch-dashboard` into the project that best represents
the profile: a small control panel for personal services, with screenshots,
smoke tests, deployment notes, and a path toward Docker/Ansible automation.
