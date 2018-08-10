pipeline {
    agent any

    stages {
        stage ('Install stage') {

            steps {
                withMaven(maven : 'maven_3_5_4') {
                    sh 'mvn clean install'
                }
            }
        }
      }
    }  
