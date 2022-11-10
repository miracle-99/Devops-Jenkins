pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Makefile') {
            steps {
                bash 'make all'
            }
        }
    }
}
