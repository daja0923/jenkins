Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
//                 sh 'mvn --version'
                sh 'javac src/main/java/Main.java'
            }
        }
    }
}
