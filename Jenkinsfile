pipeline {
  agent any 
    stages {
      stage("Compile") {
        steps {
          sh "./gradlew build"
        }
      }
      stage("Unit Tests") {
        steps {
          sh "./gradlew test"
        }
      }
    }
  }

    
