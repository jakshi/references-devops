# DevOps
## What is DevOps

* https://theagileadmin.com/what-is-devops/
* What Team Structure is Right for DevOps to Flourish? http://web.devopstopologies.com/

### General definition
DevOps is the practice of operations and development engineers participating together in the entire service lifecycle, from design through the development process to production support. 

### Extended definition
DevOps is CRISP approach with CALMS as its principles and values

CRISP:

* C – Collaborative way of working between Dev and Ops (One Team – One Goal)
* R – Repeatable process using principles and practices to provide better results to deliver the QUALITY and STABLE product/application
* I – Iterative and Incremental approach for continuous improvement
* S – Saleable across multiple teams of the product
* P – People, Principle, Practices and process oriented disciplinary collaborative approach

CALMS:

* C – Culture (promotes collaborative and open culture between Dev and Ops)
* A – Automation (automate wherever applicable)
* L- Learning (continuous learning & experimentation)
* M – Measure (Measure with shared metrics across the Dev and ops for better management)
* S – Sharing (Shared delivery process across Dev and Ops to build , deploy, maintain and monitor product with mentality of One Team – One Goal)

### Additional notes
DevOps is also characterized by operations staff making use many of the same techniques as developers for their systems work. 

### My personal definition/view/notes

* DevOps is using agile development practices and agile culture in application to managing IT infrastructure.
* The goal is also the same - faster delivery, faster feedback cycle.
* DevOps is about Continuous Improvement idea.
* And important part of that idea is 'no blame' culture.
* There're several definition of DevOps around the net.
* Personally I like CALMS definition of continuous improvement cycle:
  * Culture (no blame, collaboration, openness)
  * Automation (Infrastructure as a Code and automation in general)
  * Learning (continuous learning)
  * Measurement (agile monitoring)
  * Sharing ( again - collaboration, teams can do more than 1 person)
* I would like to note that DevOps usually doesn't work partially.
* For example: if you would remove Measurement (It seems strange - but I saw companies that did exactly that) - you would break that self-improvement cycle.
* If culture will be removed - people will be afraid to move fast (as people that do nothing - don't do mistakes)

## Blameless culture

* Imagine there’s no human error…: https://surfingcomplexity.blog/2022/05/30/imagine-theres-no-human-error/
* The infinite hows: https://www.oreilly.com/radar/the-infinite-hows/

## Observability/Monitoring

* https://github.com/sourcegraph/checkup
* https://www.opsdash.com
* https://cloud.google.com/monitoring/
* https://prometheus.io/
* http://www.servermonitoring.me
* High Performance Open Source Time Series Database & Monitoring Solutions: https://victoriametrics.com/

### Blackbox monitoring

* https://statuscake.com
* https://www.site24x7.com

### Centralized logging

* ChaosSearch: https://www.chaossearch.io/pricing
* Logz.io: https://logz.io/
* Leveraging Amazon S3 with Athena for Cost Effective Log Management: https://autify.com/blog/optimizing-cloud-application-log-management/

## CI/CD
### MLOps

* MLOps and DevOps: Why Data Makes It Different: https://www.oreilly.com/radar/mlops-and-devops-why-data-makes-it-different/

### CD/Build tools

* Everything you need to know about monorepos, and the tools to build them: https://monorepo.tools/

## Mac OS X
### Configure mac os x command line prompt

* https://www.kirsle.net/wizards/ps1.html
* http://osxdaily.com/2013/02/05/improve-terminal-appearance-mac-os-x/

### e2fs on mac os x

* https://www.paragon-software.com/home/extfs-mac/

### upgrading bash on mac os x

* https://itnext.io/upgrading-bash-on-macos-7138bd1066ba

### brew tips and tricks

* https://stackoverflow.com/questions/3987683/homebrew-install-specific-version-of-formula?noredirect=1&lq=1
* https://zoltanaltfatter.com/2017/09/07/Install-a-specific-version-of-formula-with-homebrew/

### HotKeys

* https://pqrs.org/osx/karabiner/

### Automation

* https://github.com/Hammerspoon/hammerspoon

## Infrastructure as a code (IaaC)
### Terraform

* https://github.com/coinbase/geoengineer
* https://www.contino.io/insights/top-3-terraform-testing-strategies-for-ultra-reliable-infrastructure-as-code
* https://github.com/contino/terraform-best-practice

#### Terraform modules

* Module Sources: https://developer.hashicorp.com/terraform/language/modules/sources#github
* Using Private Git Repositories as Terraform Modules: https://wahlnetwork.com/2020/08/11/using-private-git-repositories-as-terraform-modules/

#### Terraform run by developers

* https://medium.com/runatlantis/putting-the-dev-into-devops-why-your-developers-should-write-terraform-too-d3c079dfc6a8
* https://www.runatlantis.io

#### Capturing infrastructure

* https://github.com/dtan4/terraforming
* https://github.com/GoogleCloudPlatform/terraformer

### SaltStack (Salt)

* Minion did not retrun. [No response]: https://www.reddit.com/r/saltstack/comments/12kzqon/minion_did_not_retrun_no_response/

## Docker
### Security

## Chatops
### Hubot

* https://hubot.github.com/docs/scripting/
* https://gist.github.com/schisamo/46eafba27d43c4a1e026

## Slack
### integrations and libraries for different languages

* https://api.slack.com/community

## Hugo

* http://rcoedo.com/post/hugo-static-site-generator/

## Kubernetes

* https://medium.com/uptime-99/kubernetes-202-making-it-fully-operational-7416e4bb15ab
* https://blog.openai.com/scaling-kubernetes-to-2500-nodes/
* How to Pass a Configuration File to a Kubernetes Pod: https://towardsdatascience.com/how-to-pass-a-configuration-file-to-a-kubernetes-pod-61c1bcd286a5

### Cost management

* Kubecost | Kubernetes cost monitoring and management: https://www.kubecost.com/

### Tools

### 0-downtime deployment

### DNS delays

### Networking

* https://www.stackrox.com/post/2020/01/kubernetes-networking-demystified/

### CPU throttling

* https://erickhun.com/posts/kubernetes-faster-services-no-cpu-limits/

### Autoscaling

* https://learnk8s.io/kubernetes-autoscaling-strategies#exploring-pod-autoscaling-lead-time

## Git/Github

* How To Work With Multiple Github Accounts on a single Machine: https://gist.github.com/rahularity/86da20fe3858e6b311de068201d279e3
* Git mistakes from Julia Evans: https://gist.github.com/jvns/f7d2db163298423751a9d1a823d7c7c1
