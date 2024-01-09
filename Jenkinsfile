pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                bat 'your-build-command'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                bat 'your-test-command'
            }
        }
    }
}
