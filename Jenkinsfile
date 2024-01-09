pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'build-command'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'test-command'
            }
        }
    }
}
