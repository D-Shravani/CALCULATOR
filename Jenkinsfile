pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'javac Calculator.java'
            }
        }

        stage('Test') {
            steps {
                bat 'echo 6 7 + |
                java Calculator'
            }
        }
    }
}
