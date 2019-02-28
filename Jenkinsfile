#!/usr/bin/env grrovy

pipeline {
	agent  {node { ... }}
	  
stages {
         stage('Build') {
	   steps {
		 echo "welcome to build evironament"
		 sh 'java --version'
		 } 
		
	     }
	  stage('Test') {
	     steps {
		   echo "welcome to build evironament"
		   sh 'cal'
		   }
	  }
	 stage('Stage') {
	     steps {
           	    echo "welcome to build evironament"
		    sh 'cat /etc/passwd'
		   } 
	     }
     }   

}
