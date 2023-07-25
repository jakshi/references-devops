# DevSecOps
## Cryptography in general

* Cryptographic Best Practices: https://gist.github.com/atoponce/07d8d4c833873be2f68c34f9afc5a78a

## SSL/TLS
### SSL/TLS Test site

* [ENG] https://www.ssllabs.com/ssltest/analyze.html

### Let's encrypt

* [ENG] https://habrahabr.ru/post/318952/
* [ENG] https://opensource.com/article/20/2/ssl-demand

### TLS ciphers

* [ENG] https://security.stackexchange.com/questions/72926/is-tls-ecdhe-rsa-with-aes-128-cbc-sha256-a-safe-cipher-suite-to-use
* [ENG] Cloudflare - Cipher suites — Edge certificates: https://developers.cloudflare.com/ssl/ssl-tls/cipher-suites/

## Secure file transfer

* [ENG] https://magic-wormhole.readthedocs.io/en/latest/welcome.html#installation

## Share secrets
### Hashicorp Vault

* [RUS] https://habrahabr.ru/post/306812/
* [ENG] https://blog.gruntwork.io/a-guide-to-automating-hashicorp-vault-1-auto-unsealing-b219970f02c6

### Sealed secrets

* [ENG] Why you should avoid Sealed Secrets in your GitOps deployment: https://dnastacio.medium.com/why-you-should-avoid-sealed-secrets-in-your-gitops-deployment-e50131d360dd

## Jenkins secrets

* [ENG] Accessing and dumping Jenkins credentials: https://www.codurance.com/publications/2019/05/30/accessing-and-dumping-jenkins-credentials

## Password managers

* [ENG] https://medium.com/@QuantopianCyber/head-to-head-evaluation-of-five-password-managers-8faa4851c767

## WebApps security

* [ENG] https://odino.org/web-security-demistified/

## Hashing passwords

* [ENG] Storing passwords in DB: https://nakedsecurity.sophos.com/2013/11/20/serious-security-how-to-store-your-users-passwords-safely/
* [ENG] Where should we hash password frontend or backend: https://security.stackexchange.com/questions/110948/password-hashing-on-frontend-or-backend
* [ENG] OWASP - Password Storage Cheat Sheet: https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html

## Security testing services and tools

* [ENG] https://github.com/nccgroup/ScoutSuite
* [ENG] https://cloudsploit.com/
* [ENG] https://aws.amazon.com/guardduty/pricing/ - tried, not impressed, results are controversial.
* [ENG] https://detectify.com/
* [ENG] https://www.tinfoilsecurity.com/#
* [ENG] https://crashtest-security.com/pricing/ 

## Crack WiFi passwords

* [RUS] https://habrahabr.ru/post/347658/

## Interesting vulnerabilities

* [ENG] The Invisible JavaScript Backdoor: https://certitude.consulting/blog/en/invisible-backdoor/

## Github

* [ENG] You can use a CODEOWNERS file to define individuals or teams that are responsible for code in a repository: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners

### Github actions assume roles

* [ENG] Secure deployments with OpenID Connect & GitHub Actions now generally available: https://github.blog/2021-11-23-secure-deployments-openid-connect-github-actions-generally-available/
* [ENG] GitHub Actions and no AWS credentials: https://grrr.tech/posts/2021/github-actions-assume-role/
* [ENG] Connect GitHub Actions and AWS using OIDC: https://sixfeetup.com/blog/aws_access_key_id-and-github-actions-secrets
* [ENG] Securely Access Your AWS Resources From Github Actions: https://benoitboure.com/securely-access-your-aws-resources-from-github-actions
* [ENG] AWS credential and region environment variables for use in other GitHub Action: https://github.com/aws-actions/configure-aws-credentials
