pipeline {
  agent none
  stages {
    stage('lint') {
      steps {
        echo 'lint'
      }
    }

    stage ('builds') {
      parallel {
        stage('build a') {
          steps {
            echo 'a'
          }
        }

        stage('build b') {
          steps {
            echo 'b'
          }
        }

      }
    }

  }
}
