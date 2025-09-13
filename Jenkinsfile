pipeline {
    # node label aproach
    #agent { label 'ubnutu-cj-agent' }
    #node agent approach - recommand for multi agent
    agent jenkins-node-cj
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
