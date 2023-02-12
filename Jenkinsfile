pipeline {
    agent { docker { image 'python:3.10.7-alpine' } }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                pip  pip3 install PyPDF2
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                python3 helloworld.py
                python3 helloworld.py 
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                '''
            }
        }
    }
}
