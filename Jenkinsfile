pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World from jenkins pipeline"'
                sh '''
                    javac src/main/java/Main.java
                    ls -lah
                '''
            }
        }
    }
}
