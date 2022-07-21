pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'docker version'
                sh 'helm version'
            }
        }
    }
}
