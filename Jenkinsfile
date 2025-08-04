pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'echo Hello World'
                bat 'javac Hello.java'
                bat 'java Hello.java'
            }
        }
    }
}
