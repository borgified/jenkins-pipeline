pipeline {
  agent none
  stages {
    stage('lint') {
      steps {
        echo 'lint'
      }
    }

    stage('build') {
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
