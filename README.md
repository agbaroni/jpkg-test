# Quarkus - jpackage

## Build

```
./mvn clean package
```

## Make the package

```
jpackage --type app-image --app-version 0.1.0-SNAPSHOT --description 'A test app' --name Test --dest . --input target/OUTPUT --main-jar Test.jar
```

## Run the application

```
./Test/bin/Test
```
