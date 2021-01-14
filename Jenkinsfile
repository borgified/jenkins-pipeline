pipeline {
  agent none
  stages {
    stage('lint') {
      steps {
        echo 'lint'
      }
    }

    stage('build a') {
      parallel {
        stage('build') {
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