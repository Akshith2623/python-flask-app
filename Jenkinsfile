pipeline {
    agent any

    stages {
        stage('Setup') {
            steps {
                sh 'python3 --version'
                sh 'python3 -m pip install --upgrade pip'
                sh 'python3 -m pip install -r requirements.txt'
            }
        }
    }
}
