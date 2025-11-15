pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/rushikeshnkulkarni/javajenkis.git'
            }
        }
        stage('Compile') {
            steps {
                sh 'javac hello.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java hello'
            }
        }
    }
}