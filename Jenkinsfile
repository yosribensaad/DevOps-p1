pipeline {
    agent any
    stages {
        stage('Check Versions of Tools') {
            steps {
                echo 'Checking Git version...'
                sh 'git --version'
                sh 'ls'
                sh 'cat RREADME.md'
            }
        }
    }
}
