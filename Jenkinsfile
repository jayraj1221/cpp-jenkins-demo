pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'g++ main.cpp -o main'
            }
        }
        stage('Test') {
            steps {
                sh './main'
            }
        }
    }
}
