# DevOps
## What is DevOps

* [ENG] https://theagileadmin.com/what-is-devops/
* [ENG] http://web.devopstopologies.com/
* [RUS} https://habr.com/en/company/jugru/blog/487958/

### [ENG] General definition
DevOps is the practice of operations and development engineers participating together in the entire service lifecycle, from design through the development process to production support. 

### [ENG] Extended definition
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

### [ENG] Additional notes
DevOps is also characterized by operations staff making use many of the same techniques as developers for their systems work. 

### [ENG] My personal definition/view/notes

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

## Linux performance

* [ENG] http://www.brendangregg.com/linuxperf.html

### Profiling

* [RUS] https://habr.com/en/company/first/blog/442738/
* [ENG] https://jvns.ca/perf-zine.pdf

## Networking misc
### nf_conntrack: table full error

* [ENG] http://pc-freak.net/blog/resolving-nf_conntrack-table-full-dropping-packet-flood-message-in-dmesg-linux-kernel-log/

## TCP queues

* [ENG] http://engineering.chartbeat.com/2014/01/02/part-1-lessons-learned-tuning-tcp-and-nginx-in-ec2/
* [ENG] http://veithen.github.io/2014/01/01/how-tcp-backlog-works-in-linux.html

## VPN
## Helpers/Easy VPN setup

* [ENG] https://github.com/hwdsl2/setup-ipsec-vpn
* [ENG] https://github.com/jlund/streisand

## Emails
### SPF, DKIM, DMARC and e-mail tools

* [RUS] https://habrahabr.ru/company/mailru/blog/315778/
* [ENG] http://mxtoolbox.com/SuperTool.aspx?action=spf%3ayourdomain.com&run=toolpage
* [ENG] https://en.wikipedia.org/wiki/Sender_Policy_Framework
* [ENG] http://stackoverflow.com/questions/28311649/are-sites-without-wildcard-spf-records-vulnerable-to-subdomain-spoofing-attacks
* [ENG] sa-test@sendmail.net

### Spam traps

* [ENG] http://blog.mailchimp.com/where-spam-traps-come-from-and-how-they-work/

### Google Cloud restrictions for SMTP ports

* Google cloud blocks port 25, we need to use 2525 port for google cloud postfix.
* [ENG] https://cloud.google.com/vpc/docs/firewalls#blockedtraffic

### Microsoft (outlook) smpt servers block lists

* https://answers.microsoft.com/en-us/outlook_com/forum/all/hotmailoutlook-block-list-s3140-blocks-all-new/699f3a56-406e-4804-97e2-cbe23b9bb01c
* https://blog.paranoidpenguin.net/2020/08/outlook-com-is-no-longer-blocking-my-mail-server/
* https://sendersupport.olc.protection.outlook.com/snds/

## Monitoring

* [ENG] https://github.com/sourcegraph/checkup
* [ENG] https://www.opsdash.com
* [ENG] https://cloud.google.com/monitoring/
* [ENG] https://prometheus.io/
* [ENG] http://www.servermonitoring.me

### Blackbox monitoring

* [ENG] statuscake.com

## CI/CD
### MLOps

* MLOps and DevOps: Why Data Makes It Different: https://www.oreilly.com/radar/mlops-and-devops-why-data-makes-it-different/

## MySQL
### MySQL memory

* https://github.com/MarkLeith/dbahelper
* https://bugs.mysql.com/bug.php?id=72322

### MySQL SQL dialect

* https://www.jooq.org/translate/

### MySQL Developers DBs

* https://habr.com/en/company/citymobil/blog/492172/

## SSH

* [ENG] https://www.blackmoreops.com/2016/11/08/top-30-ssh-shenanigans/
* [ENG] https://medium.com/uber-security-privacy/introducing-the-uber-ssh-certificate-authority-4f840839c5cc#.s7j1vkoat
* [ENG] https://gravitational.com/blog/replace-static-ssh-keys-with-github-oauth/
* [ENG] https://smallstep.com/blog/diy-single-sign-on-for-ssh/
* [RUS] https://habr.com/post/435546/

## Git

* [ENG] https://jwiegley.github.io/git-from-the-bottom-up/
* [ENG] https://hackernoon.com/lesser-known-git-commands-151a1918a60#.l48pn1p8i
* [RUS] https://habrahabr.ru/company/mailru/blog/318508/

### How to undo stuff in git

* [ENG] https://github.blog/2015-06-08-how-to-undo-almost-anything-with-git/
* [ENG] https://medium.com/@CarrieGuss/how-to-recover-from-a-git-hard-reset-b830b5e3f60c#.353djvmkb

## Systemd

* [ENG] https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/7/html/System_Administrators_Guide/sect-Managing_Services_with_systemd-Unit_Files.html
* [ENG] https://fedoramagazine.org/systemd-converting-sysvinit-scripts/
* [RUS] https://habrahabr.ru/company/centosadmin/blog/315706/
* [ENG] https://www.linux.com/topic/networking/5-systemd-tools-you-should-start-using-now/

## Logging
### Ownership of nginx log directory and issues around that

* [ENG] http://serverfault.com/questions/639128/nginx-logging-to-access-log-1-instead-of-access-log-logrotate-failing

### rsyslog

* [RUS] https://habr.com/en/post/321262/
* [ENG] http://www.rsyslog.com/doc/master/index.html
* [ENG] https://github.com/rsyslog/rsyslog/blob/master/ChangeLog

#### Multiple SSL-TLS remote targets for rsyslog

* [ENG] http://stackoverflow.com/questions/22052111/rsyslog-logging-to-multiple-servers-with-different-tls-configurations

#### rsyslog rulesets

* [ENG] http://www.rsyslog.com/doc/v8-stable/concepts/multi_ruleset.html

## Authentication
### 2FA

* [ENG] https://code.google.com/p/google-authenticator-apache-module/wiki/GoogleAuthenticatorApacheModule
* [ENG] https://factored.readthedocs.org/en/latest/

### OAuth

* [ENG] https://github.com/bitly/oauth2_proxy

## AWS
### Util to check which instances are covered by reserved instances

* [ENG] https://github.com/balanced-ops/ec2-cost-tools

#### Install ec2-cost-tools

```
git clone git@github.com:balanced-ops/ec2-cost-tools.git
cd ec2-cost-tools
pip install -e .
export AWS_ACCESS_KEY_ID=<Your aws access key>
export AWS_SECRET_ACCESS_KEY=<Your aws secret key>

ec2-costs us-east-1
```

### S3 Bucket ACLs

* https://blogs.aws.amazon.com/security/post/Tx1P2T3LFXXCNB5/Writing-IAM-policies-Grant-access-to-user-specific-folders-in-an-Amazon-S3-bucke

### Kubernetes

* https://aws.amazon.com/blogs/opensource/introducing-fine-grained-iam-roles-service-accounts/

### Security

* [ENG] Top 10 security best practices for securing backups in AWS: https://aws.amazon.com/blogs/security/top-10-security-best-practices-for-securing-backups-in-aws/

## IaaS providers
### Cheap ones

* https://www.digitalocean.com/

## Mac OS X
### Configure mac os x command line prompt

* [ENG] https://www.kirsle.net/wizards/ps1.html
* [ENG] http://osxdaily.com/2013/02/05/improve-terminal-appearance-mac-os-x/

### e2fs on mac os x

* [ENG] https://www.paragon-software.com/home/extfs-mac/

### upgrading bash on mac os x

* [ENG] https://itnext.io/upgrading-bash-on-macos-7138bd1066ba

### brew tips and tricks

* [ENG] https://stackoverflow.com/questions/3987683/homebrew-install-specific-version-of-formula?noredirect=1&lq=1
* [ENG] https://zoltanaltfatter.com/2017/09/07/Install-a-specific-version-of-formula-with-homebrew/

### HotKeys

* [RUS] https://geektimes.ru/post/278664/
* [ENG] https://pqrs.org/osx/karabiner/

### Automation

* [ENG] https://github.com/Hammerspoon/hammerspoon

## Terraform

* [ENG] https://github.com/coinbase/geoengineer
* [ENG] https://www.contino.io/insights/top-3-terraform-testing-strategies-for-ultra-reliable-infrastructure-as-code
* [ENG] https://github.com/contino/terraform-best-practice

### Terraform run by developers

* https://medium.com/runatlantis/putting-the-dev-into-devops-why-your-developers-should-write-terraform-too-d3c079dfc6a8
* https://www.runatlantis.io

### Capturing infrastructure

* [ENG] https://github.com/dtan4/terraforming
* [ENG] https://github.com/GoogleCloudPlatform/terraformer

## Docker
### Security

* [RUS] https://habrahabr.ru/post/333402/

## Chatops
### Hubot

* [ENG] https://hubot.github.com/docs/scripting/
* [ENG] https://gist.github.com/schisamo/46eafba27d43c4a1e026

## Slack
### integrations and libraries for different languages

* [ENG] https://api.slack.com/community

## Sysdig

* [ENG] https://www.wireshark.org/docs/dfref/s/sysdig.html
* [ENG] https://groups.google.com/forum/#!topic/sysdig/Jblu9qumGH4
* [ENG] https://github.com/draios/sysdig/wiki/Sysdig-User-Guide
* [ENG] https://sysdig.com/fascinating-world-linux-system-calls/
* [ENG] https://wiki.mikejung.biz/Sysdig#Sysdig_Process_and_Thread_Related_Fields
* [ENG] http://bencane.com/2014/04/18/using-sysdig-to-troubleshoot-like-a-boss/
* [ENG] http://www.sysdig.org/wiki/sysdig-user-guide/
* [ENG] http://www.sysdig.org/wiki/sysdig-examples/

## Hugo

* [ENG] http://rcoedo.com/post/hugo-static-site-generator/

## EFI

* [ENG] https://habrahabr.ru/post/314412/

## WiFi
### WiFi CLI

* [RUS] https://habrahabr.ru/post/315960/

## Kubernetes

* [ENG] https://medium.com/uptime-99/kubernetes-202-making-it-fully-operational-7416e4bb15ab
* [ENG] https://blog.openai.com/scaling-kubernetes-to-2500-nodes/
* [RUS] https://habr.com/company/jugru/blog/416161/

### Tools

* [RUS] https://habr.com/company/mailru/blog/425343/
* [RUS] https://habr.com/company/flant/blog/426985/

### 0-downtime deployment

* [RUS] https://habr.com/en/company/flant/blog/489994/

### DNS delays

* [RUS] https://habr.com/en/post/503032/

### Networking

* [ENG] https://www.stackrox.com/post/2020/01/kubernetes-networking-demystified/

### CPU throttling

* [ENG] https://erickhun.com/posts/kubernetes-faster-services-no-cpu-limits/

### Autoscaling

* [ENG] https://learnk8s.io/kubernetes-autoscaling-strategies#exploring-pod-autoscaling-lead-time

