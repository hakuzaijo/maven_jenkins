pipeline {
  agent any
  stages {
  stage('maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: 'null', jdk: 'JAVA', maven: 'MVN_HOME', mavenSettingsConfig: 'null')   {
    sh 'mvn clean install' 
}
    }
  }

}

  
}
