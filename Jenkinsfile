pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git url: 'https://github.com/nareshh49/java-pl72421.git'
                sh 'ls -lart'
                sh 'javac sumoftwonumbers.java'
            }
        }
        stage('Run') {
            steps {
                sh 'ls -lsrt'
                sh 'java Addition'
            }
        }
    }
}
