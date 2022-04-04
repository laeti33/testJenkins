pipeline {
  agent any
  stages {
    stage('prepare') {
      steps {
        git(url: 'http://localhost:8090/blue/organizations/jenkins/pipeline-editor/testJenkins/', branch: 'master')
      }
    }

  }
}