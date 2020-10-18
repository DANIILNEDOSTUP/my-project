##### status of last deploy
    
  <img src="https://github.com/DANIILNEDOSTUP/my-project/workflows/Java-CI-with-Gradle/badge.svg?branch=master"><br>

##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
