#!/usr/bin/env grrovy

pipeline {
	agent  any
	  
stages {
	 stage('Dev') {
	   steps {
		 echo "welcome to Dev evironament"
                 sh "pwd"
		 sh "mvn --versio"
		 } 
	    
		
	     }
         stage('Build') {
	   steps {
		 echo "welcome to Build evironament"
		 
		 } 
		
	     }
	  stage('Test') {
	     steps {
		   echo "welcome to Test evironament"
		 
	     }
	  }
	 stage('Stage') {
	     steps {
           	    echo "welcome to Pre-prod evironament"
		    
		   } 
	     }
	stage('Production') {
	   steps {
		 echo "welcome to production evironament"
		 
		 } 
		
	     }
     }   

}
