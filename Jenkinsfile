pipeline {
    agent {
        label('agent')
    }
    stages {
        stage('Test') {
            steps {
                sh 'echo hola'
            }
        }
        stage('Is there any python?') {
            steps {
                sh 'python --version'
            }
        }
    }
}
