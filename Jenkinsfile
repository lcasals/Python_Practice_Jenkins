pipeline {
    agent none
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                echo "doing build stuff.."
                sh 'python helloworld.py'
                
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
