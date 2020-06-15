pipeline {
    agent any 

   stage('Deliver for development') {
            when {
                branch 'master'
            }
            steps {
                sh 'cat readme.md'
               
            }
        }
        stage('Deploy for production') {
            when {
                branch 'zzz'
            }
            steps {
                sh 'cat README.md'
                
            }
        }
    }
