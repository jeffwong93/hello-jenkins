pipeline {
    agent any

    stages {
        stage('checkout'){
            steps {
                checkout scm 
            }
        }

        stage('Run Python'){
            steps {
                bat 'python hello.py'
            }
        }
    }
}