# How to
In general it's east to configure AWS SSO for CLI utils.

But there is a nuance - A lot of CLI utils doesn't support `[sso-session some-session]` in `~/.aws/config`

Usually apps that doesn't support `[sso-session supercorp]` would complain with errors similar to : `profile "default" is configured to use SSO but is missing required configuration: sso_region, sso_start_url`

So normal `~/.aws/config` setup looks like:


```
[default]
sso_session = supercorp
sso_account_id = 111111111111
sso_role_name = AWSAdministratorAccess
region = ap-southeast-1

[profile dev]
sso_session = supercorp
sso_account_id = 222222222222
sso_role_name = AWSAdministratorAccess
region = ap-southeast-1

[sso-session supercorp]
sso_start_url = https://supercorp.awsapps.com/start#/
sso_region = ap-southeast-1
sso_registration_scopes = sso:account:access
```

But for apps that doesn't support `[sso-session supercorp]` you need to add:

```
[profile legacy-app]
sso_start_url = https://supercorp.awsapps.com/start#/
sso_region = ap-southeast-1
sso_account_id = 1111111111111
sso_role_name = AWSAdministratorAccess
region = ap-southeast-1
```

To your `~/.aws/config`

And authenticate to it with `aws sso login --profile legacy-app`

# References

* Token provider configuration with automatic authentication refresh for AWS IAM Identity Center (successor to AWS Single Sign-On): https://docs.aws.amazon.com/cli/latest/userguide/sso-configure-profile-token.html
* Legacy non-refreshable configuration for AWS IAM Identity Center (successor to AWS Single Sign-On): https://docs.aws.amazon.com/cli/latest/userguide/sso-configure-profile-legacy.html
