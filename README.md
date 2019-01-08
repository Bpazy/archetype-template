# archetype-template
this is my private archetype template

## Build archetype
```shell
$ # 1. generate archetype template from this project
$ mvn clean archetype:create-from-project -Darchetype.properties=./archetype.properties

$ # 2. install archetype
$ cd target/generated-sources/archetype/
$ mvn install

$ # 3. deploy
$ mvn deploy
```
