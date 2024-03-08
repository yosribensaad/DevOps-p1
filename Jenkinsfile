pipeline {
    agent any
    stages {
        stage('Check git version and READ.me content') {
            steps {
                echo 'Checking Git version...'
                sh 'git --version'
                sh 'ls'
                sh 'cat README.md'
            }
        }
    }
}
