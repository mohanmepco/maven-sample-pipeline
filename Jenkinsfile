pipeline {
   agent any
   tools {
       maven 'apache-maven-3.5.4'
	   jdk 'JDK'
	   }
	   stages {
	       stage ('Initialize'){
		      steps {
			     sh '''
				      echo "PATH = ${PATH}"
					  echo "M2_HOME = ${M2_HOME}"
					'''
				}
			}
			stage ('Build'){
			    steps {
				  echo 'this is a minimal pipeline.'
				 }
			}
		}
	}
