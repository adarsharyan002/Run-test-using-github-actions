pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                nodejs('Node'){
                sh 'npm install'
                
            }
            }
        }

        stage('Test') {
            steps {
                nodejs('Node'){
                
                sh 'npm run test'
            }
            }
        }

        stage('Deploy') {
            steps {
                echo "hello all done"
            }
        }
    }
}
