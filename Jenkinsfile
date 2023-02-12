pipeline {
   agent {
        docker { image 'python:3' }
    }
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
                sh 'pip --version'
            }
        }
        stage('Build') {
            steps {
                echo "Building.."
                echo "doing build stuff.."
                //sh 'python3 hello.py'
                
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
