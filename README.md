# Zerops x Docker

```yaml
project:
  name: docker
services:
  - hostname: app
    type: docker@26.1.5
    buildFromGit: https://github.com/zeropsio/recipe-docker
    enableSubdomainAccess: true
```
