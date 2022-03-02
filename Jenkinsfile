pipeline {
    agent any
    
    stages ('compile stage') {
        steps {
            withMaven(maven: 'maven 3.8.4'){
                      sh 'mvn clean compile'
                      }
                      }
                      }
                      
        stage('Testing stage') {
            steps {
                withMaven(maven: 'maven 3.8.4'){
                      sh 'mvn test'
                      }
                      }
                      }
                    stage ('Deployment stage'){
                        steps {    
                            withMaven(maven: 'maven 3.8.4'){
                                       sh 'mvn deploy'
                                       }
                                       }
                                       }
                                       }
         
