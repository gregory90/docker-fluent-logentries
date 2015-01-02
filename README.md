### Overview
Log data from docker host through fluent to logentries.

```
docker run -v /var/lib/docker/containers:/var/lib/docker/containers -e TOKEN={TOKEN} gregory90/fluent-logentries
```

##### Environment variables
TOKEN - token from logentries
