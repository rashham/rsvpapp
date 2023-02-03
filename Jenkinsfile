pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python3 tests/__init__.py'
                sh 'python3 tests/test_rsvpapp.py'
            }
        }
    }
}

