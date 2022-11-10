pipeline {
    agent any

    stages {
        stage('Git Clone') {
            steps {
                echo 'Cloning'
            }
        }
        stage('Makefile') {
            steps {
                sh 'make all'
            }
        }
        stage('Building') {
            steps {
                echo 'Build Successful'
            }
        }
    }
}
