pipeline {
    agent { docker { image 'maven:3.8.4-openjdk-11-amd64' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
