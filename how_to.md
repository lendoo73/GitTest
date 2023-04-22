## Compile the java program

```sh
javac HelloWorld.java
```

## Run the java program

```sh
java HelloWorld
```

## Execute Windows batch command

```cls
cd c:\Codes\Java\Udemy\Jenkins_-_The_Complete_Tutorial___Master_CICD_and_DevOps\Simple_java_program\
javac HelloWorld.java
java HelloWorld
```

## Build Triggers

### Trigger builds remotely

Authentication Token: `my_very_secret_and_complicated_token`
URL: `http://localhost:8181/job/HelloWorld/build?token=my_very_secret_and_complicated_token`

#### Configure login token

http://localhost:8181/user/admin/configure

118521382615c2daa4657c6b67da47e9c7

curl -X POST "http://admin:118521382615c2daa4657c6b67da47e9c7@localhost:8181/job/HelloWorld/build?token=my_very_secret_and_complicated_token"
