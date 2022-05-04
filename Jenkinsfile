pipeline {
  agent any
  stages {
  stage('maven install') {
    steps {
      withMaven(maven: 'MAVEN_MARCIN') {
    sh 'mvn clean install' 
}
    }
  }

}

  
}
