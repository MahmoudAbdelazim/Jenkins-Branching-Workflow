pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac App.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java App'
            }
        }
    }
}