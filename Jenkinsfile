pipeline {
  agent any
  stages {
  stage('maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: 'null', jdk: 'null', maven: 'MAVEN_MARCIN', mavenSettingsConfig: 'null')  {
    sh 'mvn clean install' 
}
    }
  }

}

  
}
