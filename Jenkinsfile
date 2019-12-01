pipeline {
agent any
    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/D<>/<>.git'
            }
        }
        stage('build') {
            steps {
                bat 'python 1.py'
            }
        }
    }
}
