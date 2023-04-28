pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
            withMaven(globalMavenSettingsConfig: '', jdk: '', maven: '', mavenSettingsConfig: '')  {
            sh 'mvn clean install'
        }
      }
    }

  }
}
