pipeline {
    agent any

    stages {
        stage ('Install stage') {

            steps {
                withMaven(maven : '/opt/apache-maven-3.5.4') {
                    sh 'mvn clean install'
                }
            }
        }
      }
    }  
