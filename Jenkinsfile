pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python tests/__init__.py'
                sh 'python tests/test_rsvpapp.py'
            }
        }
    }
}

