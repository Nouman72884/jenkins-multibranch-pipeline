pipeline {      
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "running from master"'
            }
        }
        stage('Build feature') {
            steps {
                sh 'echo "running from feature1"'
            }
        }
        stage('Build feature2') {
            steps {
                sh 'echo "running from feature2"'
            }
        }
        stage('Build feature3') {
            steps {
                sh 'echo "running from feature3"'
                sh 'echo "hello world!"'
            }
        }
        stage('Build feature4') {
            steps {
                sh 'echo "running from feature4"'
            }
        }
        stage('Build feature4') {
            steps {
                sh 'echo "running from feature5"'
            }
        }
  }
}
