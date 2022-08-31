As an example, to deploy the Credit Bureau sample config to your PingAuthorize, add the following to your Helm values.yaml:

```
  envs:
    SERVER_PROFILE_URL: https://github.com/mdeller-ping/server-profiles.git
    SERVER_PROFILE_PATH: pingauthorize/credit-bureau
```
