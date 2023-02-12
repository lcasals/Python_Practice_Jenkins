pipeline {
    agent none
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                echo "doing build stuff.."
                pip install PyPDF2
                
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
