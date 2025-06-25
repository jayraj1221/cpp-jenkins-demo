pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'g++ main.cpp -o main.exe'
            }
        }
        stage('Run') {
            steps {
                bat 'main.exe'
            }
        }
    }
}
