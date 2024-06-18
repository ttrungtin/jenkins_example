/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'go version'
                sh 'echo "Hello World"'
            }
        }
    }
}