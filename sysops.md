## Linux performance

* http://www.brendangregg.com/linuxperf.html

## VPN
## Helpers/Easy VPN setup

* https://github.com/hwdsl2/setup-ipsec-vpn
* https://github.com/jlund/streisand

## Emails
### SPF, DKIM, DMARC and e-mail tools

* http://mxtoolbox.com/SuperTool.aspx?action=spf%3ayourdomain.com&run=toolpage
* https://en.wikipedia.org/wiki/Sender_Policy_Framework
* http://stackoverflow.com/questions/28311649/are-sites-without-wildcard-spf-records-vulnerable-to-subdomain-spoofing-attacks
* sa-test@sendmail.net
* 5 Ways to Check Your Sending Reputation: https://sendgrid.com/blog/5-ways-check-sending-reputation/

### Spam traps

* http://blog.mailchimp.com/where-spam-traps-come-from-and-how-they-work/

### Google Cloud restrictions for SMTP ports

* Google cloud blocks port 25, we need to use 2525 port for google cloud postfix.
* https://cloud.google.com/vpc/docs/firewalls#blockedtraffic

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

* https://www.blackmoreops.com/2016/11/08/top-30-ssh-shenanigans/
* https://medium.com/uber-security-privacy/introducing-the-uber-ssh-certificate-authority-4f840839c5cc#.s7j1vkoat
* https://gravitational.com/blog/replace-static-ssh-keys-with-github-oauth/
* https://smallstep.com/blog/diy-single-sign-on-for-ssh/

## Git

* https://jwiegley.github.io/git-from-the-bottom-up/
* https://hackernoon.com/lesser-known-git-commands-151a1918a60#.l48pn1p8i

### How to undo stuff in git

* https://github.blog/2015-06-08-how-to-undo-almost-anything-with-git/
* https://medium.com/@CarrieGuss/how-to-recover-from-a-git-hard-reset-b830b5e3f60c#.353djvmkb

## Systemd

* https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/7/html/System_Administrators_Guide/sect-Managing_Services_with_systemd-Unit_Files.html
* https://fedoramagazine.org/systemd-converting-sysvinit-scripts/
* https://www.linux.com/topic/networking/5-systemd-tools-you-should-start-using-now/

## Logging
### Ownership of nginx log directory and issues around that

* http://serverfault.com/questions/639128/nginx-logging-to-access-log-1-instead-of-access-log-logrotate-failing

### rsyslog

* http://www.rsyslog.com/doc/master/index.html
* https://github.com/rsyslog/rsyslog/blob/master/ChangeLog

#### Multiple SSL-TLS remote targets for rsyslog

* http://stackoverflow.com/questions/22052111/rsyslog-logging-to-multiple-servers-with-different-tls-configurations

#### rsyslog rulesets

* http://www.rsyslog.com/doc/v8-stable/concepts/multi_ruleset.html

## Authentication
### 2FA

* https://code.google.com/p/google-authenticator-apache-module/wiki/GoogleAuthenticatorApacheModule
* https://factored.readthedocs.org/en/latest/

### OAuth

* https://github.com/bitly/oauth2_proxy

## AWS
### AWS SSO explained 

* You only need to call`aws sso login` once for all your profiles: https://ben11kehoe.medium.com/you-only-need-to-call-aws-sso-login-once-for-all-your-profiles-41a334e1b37e
* AWS configuration files, explained: https://ben11kehoe.medium.com/aws-configuration-files-explained-9a7ea7a5b42e


### Util to check which instances are covered by reserved instances

* https://github.com/balanced-ops/ec2-cost-tools

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

* Top 10 security best practices for securing backups in AWS: https://aws.amazon.com/blogs/security/top-10-security-best-practices-for-securing-backups-in-aws/

### Inventory

* AWS Cloud Scanners: https://heldsteel7.medium.com/aws-cloud-scanners-10024e4bb16f

## GCP

* Get Performance, Costs, Security recommendation in GCP: https://console.cloud.google.com/home/recommendations?referrer=search&project=my-project

## IaaS providers
### Cheap ones

* https://www.digitalocean.com/

## Sysdig

* https://www.wireshark.org/docs/dfref/s/sysdig.html
* https://groups.google.com/forum/#!topic/sysdig/Jblu9qumGH4
* https://github.com/draios/sysdig/wiki/Sysdig-User-Guide
* https://sysdig.com/fascinating-world-linux-system-calls/
* https://wiki.mikejung.biz/Sysdig#Sysdig_Process_and_Thread_Related_Fields
* http://bencane.com/2014/04/18/using-sysdig-to-troubleshoot-like-a-boss/
* http://www.sysdig.org/wiki/sysdig-user-guide/
* http://www.sysdig.org/wiki/sysdig-examples/

## EFI

* https://habrahabr.ru/post/314412/

## Kernel

* Which process has PID 0? https://unix.stackexchange.com/questions/83322/which-process-has-pid-0

## Sync
### Rsync

* The fastest remote directory rsync over ssh archival I can muster (40MB/s over 1gb NICs): https://gist.github.com/KartikTalwar/4393116

## Backup

* Why should I switch from Restic to Borg? https://www.reddit.com/r/BorgBackup/comments/v3bwfg/why_should_i_switch_from_restic_to_borg/
* BorgBackup (short: Borg) is a deduplicating backup program. https://borgbackup.readthedocs.io/en/stable/index.html
* borgmatic is simple, configuration-driven backup software for servers and workstations. https://projects.torsion.org/borgmatic-collective/borgmatic
* Restic is a fast and secure backup program. https://restic.readthedocs.io/en/latest/010_introduction.html
