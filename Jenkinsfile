pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
               echo 'Install fake composer'
               echo 'Install fake node modules'
               sh 'chmod +x test.sh'
            }
        }
        stage('Test') { 
            steps {
                echo 'Testing...'
                sh './test.sh'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Deploying...'
            }
        }
    }
}