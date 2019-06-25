# Nexus Scripting

[docs](https://help.sonatype.com/repomanager3)
## basic rest inteface

- assets
```
https://artifact-repo.wnins.com/service/rest/v1/components?repository=docker.internal
```

- components
```
https://artifact-repo.wnins.com/service/rest/v1/assets?repository=docker.internal
```

- using the continuation token
```
https://artifact-repo.wnins.com/service/rest/v1/components?repository=docker.internal&continuationToken={{continuationToken}}
```
