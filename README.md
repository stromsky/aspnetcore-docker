# Dockerfiles

```
    docker build -t stromsky/aspnetcore:latest -t stromsky/aspnetcore:2.1 aspnetcore
    docker push stromsky/aspnetcore:latest
    docker push stromsky/aspnetcore:2.1

    docker build -t stromsky/dotnet:latest -t stromsky/dotnet:2.1 dotnet
    docker push stromsky/dotnet:latest
    docker push stromsky/dotnet:2.1

    docker build -t stromsky/node:latest -t stromsky/node:9-alpine node
    docker push stromsky/node:latest
    docker push stromsky/node:9-alpine
```