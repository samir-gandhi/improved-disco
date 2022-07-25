Steps:

First, we need to bring profiles inside images. 

pingfederate: 

```
docker build -t dev.registry.ews.int/ews/dp/ping/pingfederate:2204 -f Dockerfile.pingfederate .
```

pingdirectory

```
docker build -t dev.registry.ews.int/ews/dp/ping/pingdirectory:2204 -f Dockerfile.pingfederate .
```

push the images up to ecr. 
