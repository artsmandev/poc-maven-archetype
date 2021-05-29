Hi,\
This is a simple PoC of Maven Archetype.

* Clone the repo.\
  _Just like this_:

  ```
  cd ~/Downloads &&\
  git clone https://github.com/artsmandev/poc-maven-archetype.git
  ```

* Install the archetype local:

  ```
  cd poc-maven-archetype.git &&\
  mvn clean install
  ```

* Create a new project from that archetype.\
  _Just like this_:

  ```
  mvn archetype:generate \
  -DarchetypeCatalog=local \
  -DarchetypeGroupId=dev.artsman \
  -DarchetypeArtifactId=poc-maven-archetype \
  -DarchetypeVersion=1.0-SNAPSHOT \
  -DinteractiveMode=false \
  -DgroupId=dev.artsman \
  -DartifactId=poc-maven-archetype-test
  ```

