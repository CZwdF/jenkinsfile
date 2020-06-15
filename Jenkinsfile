pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
            git 'https://github.com/CZwdF/epam-test'
            sh 'cat README.md'
            }
        }
        stage('Test') { 
            steps {
                echo "TEST"
            }
        }
        stage('Deploy') { 
            steps {
                echo "Deploy"
            }
        }
    }
}
