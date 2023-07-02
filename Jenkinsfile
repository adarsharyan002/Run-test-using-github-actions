pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                nodejs('Node'){
                sh 'npm install'
                sh 'npm run build'
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
