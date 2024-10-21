pipeline {
    agent any
    stages {
        stage('Setup') {
            steps {
                sh 'pip install -r requirements.txt'
            }
        }
        stage('Build') {
            steps {
                sh 'python hello_world.py'
            }
        }
        stage('Test') {
            steps {
                echo 'No tests defined.'
            }
        }
    }
}
