# Getting Started
Quick spring boot example.

```
mvn spring-boot:run
```

```
curl localhost:8080/hello
```
# Deploy to Openshift

```
oc new-app codecentric/springboot-maven3-centos~https://github.com/pietro-ventura/spring-boot-ms.git
oc expose svc/spring-boot-ms

```
