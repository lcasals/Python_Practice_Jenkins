pipeline {
   agent any
    stages {
        stage('version') {
            steps {
                echo "Building.."
                sh 'python3 --version'
                
            }
        }
       stage('version2') {
            steps {
                echo "Building.."
                sh 'pip install PyPDF2'
                
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
