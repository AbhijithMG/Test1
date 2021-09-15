pipeline {
  agent any
  stages {
    stage('Code1') {
      parallel {
        stage('Code1') {
          steps {
            echo 'Sample'
          }
        }

        stage('Qualityvalidation') {
          steps {
            echo 'code scan'
          }
        }

      }
    }

    stage('Build') {
      steps {
        echo 'Build'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployed'
      }
    }

  }
}