#### create jenkins jobs with this build step

```bash
for version in `cat ${JENKINS_HOME}/sbt_versions.txt`; do until echo "$version"; do sleep 5; done; done
```
