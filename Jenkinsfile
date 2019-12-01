pipeline {
agent any
    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/D<oshri.shaul>/<O$hikatan8$>.git'
            }
        }
        stage('build') {
            steps {
                bat 'python 1.py'
            }
        }
    }
}
