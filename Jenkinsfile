pipeline {
  agent any
  stages {
  stage('maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: 'null', jdk: 'JAVA', maven: 'MVN_MARCIN', mavenSettingsConfig: 'null')   {
    sh 'mvn clean install' 
}
    }
  }

}

  
}
