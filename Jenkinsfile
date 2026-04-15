
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/rajthilaksmart-devops/pipeline-test.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Build started'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Testing'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo Deploying'
            }
        }
    }
}
