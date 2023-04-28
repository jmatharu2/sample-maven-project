pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {

      withMaven(globalMavenSettingsConfig: '', jdk: '', maven: '', mavenSettingsConfig: '') {
            'mvn clean install'
        }

      }
    }

  }
}
