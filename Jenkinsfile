
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello from Jenkins!'
            }
        }

        stage('Check Git') {
            steps {
                sh 'git --version'
            }
        }
    }
}
