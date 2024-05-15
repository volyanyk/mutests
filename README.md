## JaCoCo

I added JaCoCo plugin - it allows to generate code coverage report. To generate it, run the following command
```shell
$ ./gradlew mutations:clean mutations:test mutations:jacocoTestReport
```

Report is generated in `mutations/build/reports/jacoco/test/html` directory.

## Pitest

I also added Pitest [gradle plugin](https://gradle-pitest-plugin.solidsoft.info/). When one runs the command:
```shell
$ ./gradlew mutations:pitest
```