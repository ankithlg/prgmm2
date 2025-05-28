pipeline {
    agent any
    stages {
        stage('Run Python Script') {
            steps {
                bat 'python hello.py'
            }
        }
        stage('Show HTML Interface') {
            steps {
                bat 'start index.html'
            }
        }
    }
}