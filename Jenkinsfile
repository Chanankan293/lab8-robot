pipeline {
    agent any

    stages {
        stage('Install Robot Framework') {
            steps {
                sh 'pip3 install robotframework || true'
            }
        }

        stage('Run Robot Test') {
            steps {
                sh 'robot tests'
            }
        }
    }
}
