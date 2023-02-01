/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.10.5' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
