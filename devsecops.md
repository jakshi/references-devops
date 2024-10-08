# DevSecOps
## Cryptography in general

* Cryptographic Best Practices: https://gist.github.com/atoponce/07d8d4c833873be2f68c34f9afc5a78a

## SSL/TLS
### SSL/TLS Test site

* https://www.ssllabs.com/ssltest/analyze.html

### Let's encrypt

* https://habrahabr.ru/post/318952/
* https://opensource.com/article/20/2/ssl-demand

### TLS ciphers

* https://security.stackexchange.com/questions/72926/is-tls-ecdhe-rsa-with-aes-128-cbc-sha256-a-safe-cipher-suite-to-use
* Cloudflare - Cipher suites — Edge certificates: https://developers.cloudflare.com/ssl/ssl-tls/cipher-suites/

## Secure file transfer

* https://magic-wormhole.readthedocs.io/en/latest/welcome.html#installation

## Share secrets
### Hashicorp Vault

* https://blog.gruntwork.io/a-guide-to-automating-hashicorp-vault-1-auto-unsealing-b219970f02c6

### Sealed secrets

* Why you should avoid Sealed Secrets in your GitOps deployment: https://dnastacio.medium.com/why-you-should-avoid-sealed-secrets-in-your-gitops-deployment-e50131d360dd

## Git

* File encryption in Git Repository: https://stackoverflow.com/questions/48330742/file-encryption-in-git-repository
    * A script to configure transparent encryption of sensitive files stored in a Git repository: https://github.com/elasticdog/transcrypt

## Jenkins secrets

* Accessing and dumping Jenkins credentials: https://www.codurance.com/publications/2019/05/30/accessing-and-dumping-jenkins-credentials

## Password managers

* https://medium.com/@QuantopianCyber/head-to-head-evaluation-of-five-password-managers-8faa4851c767

## WebApps security

* https://odino.org/web-security-demistified/

## Hashing passwords

* Storing passwords in DB: https://nakedsecurity.sophos.com/2013/11/20/serious-security-how-to-store-your-users-passwords-safely/
* Where should we hash password frontend or backend: https://security.stackexchange.com/questions/110948/password-hashing-on-frontend-or-backend
* OWASP - Password Storage Cheat Sheet: https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html

## Security testing services and tools

* https://github.com/nccgroup/ScoutSuite
* https://cloudsploit.com/
* https://aws.amazon.com/guardduty/pricing/ - tried, not impressed, results are controversial.
* https://detectify.com/
* https://www.tinfoilsecurity.com/#
* https://crashtest-security.com/pricing/ 

## Crack WiFi passwords

## Interesting vulnerabilities

* The Invisible JavaScript Backdoor: https://certitude.consulting/blog/en/invisible-backdoor/

## Github

* You can use a CODEOWNERS file to define individuals or teams that are responsible for code in a repository: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners

### Github actions assume roles

* Secure deployments with OpenID Connect & GitHub Actions now generally available: https://github.blog/2021-11-23-secure-deployments-openid-connect-github-actions-generally-available/
* GitHub Actions and no AWS credentials: https://grrr.tech/posts/2021/github-actions-assume-role/
* Connect GitHub Actions and AWS using OIDC: https://sixfeetup.com/blog/aws_access_key_id-and-github-actions-secrets
* Securely Access Your AWS Resources From Github Actions: https://benoitboure.com/securely-access-your-aws-resources-from-github-actions
* AWS credential and region environment variables for use in other GitHub Action: https://github.com/aws-actions/configure-aws-credentials

## DNS
### DNS scanning

* bruteforce and resolve the subdomains with wildcard handling support: https://github.com/projectdiscovery/shuffledns

## Kubernetes

* kube-score is a tool that performs static code analysis of your Kubernetes object definitions: https://github.com/zegl/kube-score

## Containers

* Clair is an open source project for the static analysis of vulnerabilities in application containers (currently including OCI and docker): https://github.com/quay/clair
* Grype A vulnerability scanner for container images and filesystems: https://github.com/anchore/grype

## Hardware

* BootTerm is a simple, reliable and powerful terminal designed to ease connection to ephemeral serial ports as found on various SBCs, and typically USB-based ones: https://github.com/wtarreau/bootterm

## AWS

* a CLI tool for securely accessing your DB instances and other AWS resources in private networks at almost no cost: https://github.com/basti-app/basti
