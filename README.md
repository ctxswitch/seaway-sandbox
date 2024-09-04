# seaway-sandbox
Example application to exercise the [seaway](https://github.com/ctxswitch/seaway) development environment tools.

```
curl -LSso /tmp/config.yaml  https://raw.githubusercontent.com/ctxswitch/seaway/main/config/k3d/config.yaml
k3d cluster create --config /tmp/config.yaml

brew tap ctxsh/tap
brew install seactl

seactl init shared
```
