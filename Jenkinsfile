pipeline {
    agent any 
    stages {
    stage('maven install') {
      step {
            withMaven(globalMavenSettingsConfig: '', jdk: '', maven: '', mavenSettingsConfig: '') {
            'mvn clean install'
        }
      }
    }

  }
}
