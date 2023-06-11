pipeline {
    agent any

    stages {
        stage('DEV') {
            steps {
                echo 'Hello World'
            }
        }
        stage('QA') {
            steps {
                echo 'Hello World'
            }
        }
        stage('PROD') {
            steps {
                git branch: 'prod', url: 'https://github.com/sushma9911/testjune'
            }
        }
    }
}



