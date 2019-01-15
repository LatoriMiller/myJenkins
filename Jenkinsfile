pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Hello, Latori'
                sh 'pwd'
            }
        }
        stage('Test') { 
            steps {
                echo 'Hello, All'
                sh 'ls'
            }
        }
        stage('Deploy'){
            steps{
                ls
                echo 'deploying'
            }
        }
    }
}

