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

## Sysdig

* [ENG] https://www.wireshark.org/docs/dfref/s/sysdig.html
* [ENG] https://groups.google.com/forum/#!topic/sysdig/Jblu9qumGH4
* [ENG] https://github.com/draios/sysdig/wiki/Sysdig-User-Guide
* [ENG] https://sysdig.com/fascinating-world-linux-system-calls/
* [ENG] https://wiki.mikejung.biz/Sysdig#Sysdig_Process_and_Thread_Related_Fields
* [ENG] http://bencane.com/2014/04/18/using-sysdig-to-troubleshoot-like-a-boss/
* [ENG] http://www.sysdig.org/wiki/sysdig-user-guide/
* [ENG] http://www.sysdig.org/wiki/sysdig-examples/

## EFI

* [ENG] https://habrahabr.ru/post/314412/

## WiFi
### WiFi CLI

* [RUS] https://habrahabr.ru/post/315960/