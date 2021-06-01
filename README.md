# Description

* Digests and Links to usefule resources about DevOps and related topics
* Some links point to English resources and some links point to Russian resources.
  * They marked correspondingly [ENG] and [RUS] 

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

## Monitoring

* [ENG] https://github.com/sourcegraph/checkup
* [ENG] https://www.opsdash.com
* [ENG] https://cloud.google.com/monitoring/
* [ENG] https://prometheus.io/
* [ENG] http://www.servermonitoring.me

### Blackbox monitoring

* [ENG] statuscake.com

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

# DevSecOps
## SSL
### SSL Test site

* [ENG] https://www.ssllabs.com/ssltest/analyze.html

### Let's encrypt

* [ENG] https://habrahabr.ru/post/318952/
* [ENG] https://opensource.com/article/20/2/ssl-demand

## Secure file transfer

* [ENG] https://magic-wormhole.readthedocs.io/en/latest/welcome.html#installation

## Share secrets
### Hashicorp Vault

* [RUS] https://habrahabr.ru/post/306812/
* [ENG] https://blog.gruntwork.io/a-guide-to-automating-hashicorp-vault-1-auto-unsealing-b219970f02c6

## Password managers

* [ENG] https://medium.com/@QuantopianCyber/head-to-head-evaluation-of-five-password-managers-8faa4851c767

## WebApps security

* [ENG] https://odino.org/web-security-demistified/

## Storing passwords in DB

* [ENG] https://nakedsecurity.sophos.com/2013/11/20/serious-security-how-to-store-your-users-passwords-safely/

## Security testing services and tools

* [ENG] https://github.com/nccgroup/ScoutSuite
* [ENG] https://cloudsploit.com/
* [ENG] https://aws.amazon.com/guardduty/pricing/ - tried, not impressed, results are controversial.
* [ENG] https://detectify.com/
* [ENG] https://www.tinfoilsecurity.com/#
* [ENG] https://crashtest-security.com/pricing/ 

## Crack WiFi passwords

* [RUS] https://habrahabr.ru/post/347658/

# Programming
## Naming

* [ENG] http://journal.stuffwithstuff.com/2016/06/16/long-names-are-long/
* [ENG] https://swift.org/documentation/api-design-guidelines/#use-terminology-well

## SOLID

* [ENG] https://medium.com/backticks-tildes/the-s-o-l-i-d-principles-in-pictures-b34ce2f1e898

## Code Review

* [ENG] https://google.github.io/eng-practices/review/reviewer/
* [RUS] https://habr.com/en/post/473308/

## Resources in web to learn programming

* [RUS] https://habr.com/post/331530/
* [RUS] https://habr.com/post/424329/

### Gamification in programming learning

* [ENG] https://medium.mybridge.co/12-free-resources-learn-to-code-while-playing-games-f7333043de11#.vde4xt38h
* [RUS] https://habrahabr.ru/company/edison/blog/315696/

## Software development best practices

* [ENG] https://medium.com/s/story/notes-to-myself-on-software-engineering-c890f16f4e4d
* [ENG] https://www.infoq.com/articles/slow-down-go-faster
* [ENG] https://levelup.gitconnected.com/programming-habits-you-should-adopt-8ab75419fb09

## Fast programming

* [ENG] http://www.codesimplicity.com/post/the-secret-of-fast-programming-stop-thinking/

## Software design

* [ENG] https://blog.pragmaticengineer.com/software-architecture-is-overrated/

## Microservices

* [ENG] http://microservices.io/

### Testing microservices

* [ENG] https://medium.com/@copyconstruct/testing-microservices-the-sane-way-9bb31d158c16

## How to improve and work with legacy code

* [ENG] https://jacquesmattheij.com/improving-a-legacy-codebase

## Pair programming tools

* [ENG] https://atom.io/packages/atom-pair

## Google Chrome console

* [ENG] https://www.freecodecamp.org/news/10-tips-to-maximize-your-javascript-debugging-experience-b69a75859329/#.tq5dgdfbc

## AWS Lambdas

* https://github.com/serverless/serverless

## Geodata

* [ENG] http://geoawesomeness.com/top-19-online-geovisualization-tools-apis-libraries-beautiful-maps/

## shell/bash

* [ENG] https://google.github.io/styleguide/shell.xml
* [ENG] http://mywiki.wooledge.org/BashPitfalls
* [ENG] https://mywiki.wooledge.org/BashGuide
* [RUS] https://habrahabr.ru/company/mailru/blog/311762/

## Ruby
### CLI
#### Cli gems

* [ENG] https://github.com/commander-rb/commander
* [ENG] https://github.com/piotrmurach/tty-config
* [ENG] https://github.com/settingslogic/settingslogic

#### Code organization

* [ENG] https://stackoverflow.com/questions/8334684/how-to-share-variables-across-my-rb-files
* [ENG] https://guides.rubygems.org/make-your-own-gem/
* [ENG] https://openclassrooms.com/en/courses/4511061-write-object-oriented-ruby/4648256-working-in-multiple-files

#### Curl to Net::HTTP

* [ENG] https://jhawthorn.github.io/curl-to-ruby/

## Python
### CLI

* [ENG] https://github.com/google/python-fire/blob/master/docs/guide.md

### Packaging

* [ENG] https://levelup.gitconnected.com/how-to-publish-a-python-command-line-application-to-pypi-5b97a6d586f1

### Tips and Tricks

* [ENG] https://martinheinz.dev/blog/1
* [ENG] https://martinheinz.dev/blog/4

### Best practices/tools

* [ENG] https://medium.com/better-programming/understanding-best-practice-python-tooling-by-comparing-popular-project-templates-6eba49229106

## PHP
### Security

* [ENG] https://paragonie.com/blog/2017/12/2018-guide-building-secure-php-software

## Blockchain
### Etherium smart contracts

* [ENG] https://medium.com/@ConsenSys/a-101-noob-intro-to-programming-smart-contracts-on-ethereum-695d15c1dab4
* [ENG] https://arvanaghi.com/blog/how-to-set-up-a-private-ethereum-blockchain-using-geth/
* [ENG] http://hidskes.com/blog/2015/08/12/creating-a-testnet-using-geth/
* [ENG] https://github.com/ethereum/go-ethereum/wiki/Private-network
* [ENG] https://medium.com/taipei-ethereum-meetup/beginners-guide-to-ethereum-3-explain-the-genesis-file-and-use-it-to-customize-your-blockchain-552eb6265145
* [ENG] https://gist.github.com/0mkara/b953cc2585b18ee098cd

# Hiring
## Take home projects

* [ENG] https://angel.co/blog/engineers-hate-your-take-home-project-heres-how-to-fix-it

## Interview questions/guidance

* [ENG] https://github.com/yangshun/tech-interview-handbook
* [ENG] https://github.com/MaximAbramchuck/awesome-interview-questions#linux
* [ENG] https://triplebyte.com/blog/interview-questions-are-too-hard-and-too-short
* [ENG] https://sockpuppet.org/blog/2015/03/06/the-hiring-post/
* [RUS] https://habrahabr.ru/company/exante/blog/335096/
* [RUS] https://habrahabr.ru/post/339720/
* [RUS] https://habrahabr.ru/post/341220/

## Interview questions for the DevOps Engineer

* [ENG] https://github.com/jakshi/devops-interview-questions

## Interview questions for a Backend Developer

* [ENG] https://github.com/arialdomartini/Back-End-Developer-Interview-Questions

## Remote coding interview

* [ENG] https://repl.it/

# Meta-hirging resources

* [ENG] https://amazinghiring.com/
* [ENG] https://getcoder.io/

## Short digest of questions for DevOps Engineer
### General

* what have you done? which most interesting projects have you done?
* infrastructure monitoring?
* application monitoring?

### DevOps

* What is DevOps?
* Why do we need it?
* What is the purpose of a post-mortem meeting?
* What do you understand by “Infrastructure as code”? How does it fit into the DevOps methodology? What purpose does it achieve?
* Organization of CI process?
* What are the success factors for Continuous Integration?
* Organization of CD process?

### Technical
#### DB

* What’s ACID?
* Slow DB - what could be a reasons?
* MySQL upgrade from 5.6 to 8.0 what issues to you see?
* Automated DB migrations?

#### Linux

* What is the difference between hardlinks and symlinks?
* What is an inode and what fields are stored in an inode?
* What are zombie processes?

#### Network

* How does ping work? What about traceroute?
* What is IPv6? Why should we care?

#### Development

* What is your favorite scripting language? Why?
* How would you give your developers access to the production logs?
* Tell me about the worst-run/best-run outage you’ve been a part of. What made it bad/well-run?
* How would you deploy software to 5000 systems?

#### AWS

* Automation for AWS infrastructure?

## Management
## Defining tasks
### [ENG] Template from AirBnB

```
### Project Title
### Description: What is it?
...

### Problem: What problem is this solving?
...

### Why: How do we know this is a real problem and worth solving?
…

### Success: How do we know if we’ve solved this problem?
...

### Audience: Who are we building for?
...

### What: What does this look like in the product?
...

### How: What is the experiment plan?
...

### Proposed timeline: When does it ship and what are the milestones?
...
```

### [ENG] TOTE
For small tasks for juniour/middle

* T1 — Test — желаемое состояние, к которому мы стремимся, какое оно?
* О — Operation — какие действия мы должны делать, чтобы достигнуть результата?
* T2 — Test2 — по каким признакам мы поймём, что продвинулись в сторону результата?
* E — Exit — по каким критериям мы поймём, что результат окончательно достигнут?

### [RUS] Правила управления задачами.
диалог по задаче не прекращается, пока не 

* Следующие шаги должны быть описаны и конкретизированы.
* У задачи должен быть назначен один ответственный.
* Должна быть определена страховка от невыполнения.
* Назначено время, место и способ следующей контрольной точки.

## [ENG] How much guidance should you give to the team (as an engineering leader)?
If you work with mature engineers:

* out of 10 cases when you can provide guidance:
  * 1 direct guidance
  * 1-2 coaching/suggestions
  * 7-8 own solutions

## [ENG] Good Values

* We care
* Initiative is rewarded
* We understand what problem we try to solve
* We celebrate colleagues achievments 
* We have processes for people
* We open to get and provide feedback
* We presume that people are competent and know what they are doing
* We share knowledge
* We work good and rest good
* We keep humanity despite moving fast

## Good engineering manager

* [ENG] https://charity.wtf/2019/01/04/engineering-management-the-pendulum-or-the-ladder/
* [ENG] https://www.banterly.net/2019/01/06/developer-hapiness-and-where-to-find-it/
* [ENG] https://www.inc.com/justin-bariso/google-spent-a-decade-researching-what-makes-a-great-boss-they-came-up-with-these-10-things.html?cid=sf01001
* [RUS] https://habr.com/en/company/lanit/blog/481584/

### Discover value/creative management

* [ENG] https://iism.org/article/why-are-ceos-failing-software-engineers-56
* [ENG] http://www.paulgraham.com/makersschedule.html

## Good Product Manager

* [RUS] https://habrahabr.ru/company/parallels/blog/333698/

### Features Prioritization

* [RUS] https://habr.com/post/429404/

## Retrospectives

* [RUS] https://habrahabr.ru/company/mindbox/blog/347780/

## Free Day once per week

* [RUS] https://habr.com/en/post/443680/

## Organization as a product

* [ENG] https://uxdesign.cc/what-seven-years-at-airbnb-taught-me-about-building-a-company-e1d035d49c56

## Writing email

* [ENG]  https://hbr.org/2016/11/how-to-write-email-with-military-precision

## Task prioritization

* [ENG] http://www.elidedbranches.com/2019/05/opp-other-peoples-problems.html

## Software
### Kanban software

* [ENG] https://hygger.io/
* [ENG] https://trello.com/

### JIRA/Trello integration

* [ENG] unito.io

## Communication
## Async communication

* [ENG] https://doist.com/blog/asynchronous-communication/

## Empathy

* [RUS] https://habr.com/en/company/exness/blog/491208/

## Psychology for managers

* [RUS] https://habr.com/en/company/oleg-bunin/blog/473440/

## Deadlines

* [ENG] http://jatins.gitlab.io/me/why-deadline/

## Focus/pomodoro

* [RUS] https://habr.com/en/company/maxilect/blog/486238/

## OKRs - Objective Key Results

* [ENG] https://lifeclub.org/books/measure-what-matters-john-doerr-review-summary
