### Usage
```shell
git clone git@github.com:unionj-cloud/unionj-java-archetype.git

mvn clean install

mvn archetype:generate \
-DarchetypeGroupId=cloud.unionj \
-DarchetypeArtifactId=unionj-java-archetype \
-DarchetypeVersion=0.0.1-SNAPSHOT \
-DinteractiveMode=false \
\
-DgroupId=yourgroupid \
-DartifactId=yourartifactid \
-Dversion=yourversion \
-Dpackage=yourpackage
```