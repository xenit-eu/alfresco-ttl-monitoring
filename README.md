# Tech Talk Live - Open Source Monitoring for Alfresco

![ttl.png](assets/ttl.png)

Github repository with demonstrations for Alfresco Tech Talk Live about monitoring

## Starting the environment

This project uses the [Alfresco Docker Gradle Plugins](https://github.com/xenit-eu/alfresco-docker-gradle-plugin)
to easily startup an Alfresco stack including various monitoring tools and components.

Assuming Docker is correctly setup on your environment, the stack can be started by executing a single command:

```groovy
./gradlew composeUp
```
