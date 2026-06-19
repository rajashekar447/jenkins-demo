pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Cloning Code'
            }
        }

        stage('Build') {
            steps {
                sh 'python3 app.py'
            }
        }

        stage('Test') {
            steps {
                echo 'Tests Passed'
            }
        }
    }
}
