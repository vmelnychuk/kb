# Gradle Usage


## Run only one test with name 'TestClassName'
```shell
./gradlew -Dtest.single=TestClassName test
```


## List projects in build
```shell
./gradlew -q projects
```


## Run task from root project
```shell
./gradlew :services:webservice:build
```


## Examples of build commands
```shell
./gradlew clean build --continue --stacktrace --parallel
```

## Build with ignoring cached dependencies
```shell
./gradlew build --refresh-dependencies
```
