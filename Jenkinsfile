pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        gitlabCommitStatus(name: 'JenkinsGitLabStep') {
          echo 'This should update gitlab commit status'
        }
        
      }
    }
  }
}