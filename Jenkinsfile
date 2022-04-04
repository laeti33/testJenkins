pipeline {
  agent any
  stages {
    stage('prepare') {
      steps {
        git(url: 'https://github.com/laeti33/testJenkins.git', branch: 'master')
      }
    }

    stage('build') {
      steps {
        sh 'mvn clean install'
      }
    }

  }
}