node {
   def mvnHome
   stage('Preparation') { // for display purposes
      git 'https://github.com/jglick/simple-maven-project-with-tests.git'      
   }
   stage('Compile') {
      echo 'I am from Compile Statge'
	  sleep time: 3, unit: 'NANOSECONDS'
   }
   stage('Testing') {
   echo 'I am from Testing Statge'
   
	sleep time: 3, unit: 'NANOSECONDS'
   }
   stage('Deployment') {
   echo 'I am from Deployment Statge'
   
	sleep time: 3, unit: 'NANOSECONDS'
   }
}
