Steps:

First, we need to bring profiles inside images. 

pingfederate: 

```
docker build -t dev.registry.ews.int/ews/dp/ping/pingdirectory:2204 -f Dockerfile.pingfederate .
```

pingdirectory

```
docker build -t dev.registry.ews.int/ews/dp/ping/pingdirectory:2204 -f Dockerfile.pingfederate .
```# improved-disco
