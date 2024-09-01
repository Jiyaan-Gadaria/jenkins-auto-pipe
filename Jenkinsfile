pipeline {
  agent any
  stages {
    stage('unit-test') {
      steps {
        sh 'pwd'
      }
    }

    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'Jenkin\'s last session'
          }
        }

        stage('build-2') {
          steps {
            echo 'Next week will start Monitoring tool session'
          }
        }

      }
    }

  }
}