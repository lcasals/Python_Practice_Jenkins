pipeline {
   agent {
        docker { image 'node:16.13.1-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
        stage('version') {
            steps {
                echo "Building.."
                sh 'python3 --version'
                
            }
        }
        stage('Build') {
            steps {
                echo "Building.."
                echo "doing build stuff.."
                sh 'python3 helloworld.py'
                
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                echo "doing test stuff.."
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                echo "doing delivery stuff.."
            }
        }
    }
}
