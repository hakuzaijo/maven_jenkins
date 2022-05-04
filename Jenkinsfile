pipeline {
  agent any
  stages {
  stage('maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: 'null', jdk: 'JDK', maven: 'MAVEN_MARCIN', mavenSettingsConfig: 'C:\Users\mio\.jenkins\workspace\testMavenPipeline')  {
    sh 'mvn clean install' 
}
    }
  }

}

  
}
