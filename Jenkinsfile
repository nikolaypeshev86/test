pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'docker info'
                sh 'helm version'
            }
        }
    }
}
