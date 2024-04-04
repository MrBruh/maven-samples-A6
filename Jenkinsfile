pipeline {
  agent any
  tools { 
      maven 'DHT_MVN' 
      jdk 'DHT_Sense' 
  }
  stages {
    stage('check out') {
      steps {
        git(url: 'https://github.com/MrBruh/maven-samples-A6.git', branch: 'master')
      }
    }
  }
}
