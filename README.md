# blog-soapui-war
Sourcecode for blog post describing how to package your SoapUI mocks in a war-file.

## Create war-file
```
./gradlew createWar
```

## Run war-file with Jetty
```
./gradlew farmRun
```
The mock-service should now be available at http://localhost:8081/


## Run SoaUI from Gradle
```
./gradlew runSoapUI
```
During the first launch, you will have to import the project file to the newly created workspace. Do not place the workspace file under source control since it will contain absolute paths to the project file.
