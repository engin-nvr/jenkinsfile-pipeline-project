pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
        }
        stage('deneme') {
            steps {
                echo 'Running the compiled java code...'
                sh 'java Hello'
            }
        }
    }
}