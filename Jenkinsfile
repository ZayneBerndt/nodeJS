pipeline {
    agent any
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
    }
    post {
        success {
        echo 'success'

        }
        failure {

          echo 'fail'
        }
        always {
          echo 'I will always say Hello again!'
        }
    }
}
