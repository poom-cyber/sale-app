pipeline {
    agent any
    tools {
        go '1.22.0'
    }
    stages {
        stage('build') {
            steps {
                echo 'hi boi'
                sh 'go version'
            }
        }
    }
}