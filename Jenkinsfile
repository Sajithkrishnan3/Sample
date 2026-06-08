pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git branch: 'master', url: 'https://github.com/Sajithkrishnan3/Sample'
            }
        }

        stage('Compile Code') {
            steps {
                sh 'javac Demo.java'
            }
        }

        stage('Run Code') {
            steps {
                sh 'java Demo'
            }
        }
    }
}
