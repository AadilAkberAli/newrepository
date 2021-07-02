pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                javac hw.java
            }
        }
        stage('Test') {
            steps {
                java HelloWorld
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
