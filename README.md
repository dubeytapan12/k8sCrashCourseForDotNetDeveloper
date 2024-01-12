# k8s Crash Course For Dot Net Developer
# Part 2 -



<details>
<summary> Commands Used in this section- </summary>
  
 **Docker login command to login to Docker Hub**

```bash
docker login
```

**Docker ps command to list all containers**

```bash
docker ps
```

**Docker images command to list all images**

```bash
docker images
```

**list all pods**

```bash
kubectl pods
```

**Get a Shell to a Running Container**

```bash
kubectl exec -i -t pod-name -- /bin/bash
```

**Install Curl and change user of installation**
```bash
USER root
RUN apt-get update \
 && apt-get install -y curl
 USER app
