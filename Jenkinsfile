pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Test') {
      steps {
        git(url: 'https://github.com/hcastorpmyth/mythtodo', branch: 'master', poll: true)
      }
    }

  }
}