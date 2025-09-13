pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/chandrakantjadhav/herovired-practice-cicd.git'
            }
        }
        stage('Install') {
            steps {
                sh 'ls -la'
            }
        }
        stage('Build') {
            steps {
                sh 'cat test.php'
            }
        }
    }

}
