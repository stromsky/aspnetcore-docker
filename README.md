# Dockerfiles

```
    docker build -t stromsky/aspnetcore:latest -t stromsky/aspnetcore:2.0 aspnetcore
    docker push stromsky/aspnetcore:latest
    docker push stromsky/aspnetcore:2.0

    docker build -t stromsky/dotnet:latest -t stromsky/dotnet:2.0-runtime dotnet
    docker push stromsky/dotnet:latest
    docker push stromsky/dotnet:2.0-runtime

    docker build -t stromsky/node:latest -t stromsky/node:9-alpine node
    docker push stromsky/node:latest
    docker push stromsky/node:9-alpine
```