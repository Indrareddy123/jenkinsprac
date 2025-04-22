pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    // Add your build commands here
                    echo 'Building the project...'
                }
            }
        }

        stage('Test') {
            steps {
                script {
                    // Add your test commands here
                    echo 'Running tests...'
                }
            }
        }

        stage('Deploy') {
            steps {
                script {
                    // Add your deployment commands here
                    echo 'Deploying the project...'
                }
            }
        }
    }
}
