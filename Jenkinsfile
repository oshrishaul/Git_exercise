pipeline {
agent any
    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/oshrishaul/Git_exercise.git'
            }
        }
        stage('build') {
            steps {
                bat 'python 1.py'
            }
        }
    }
}
