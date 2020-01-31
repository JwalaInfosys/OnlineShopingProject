node {
   def mvnHome
   stage('Preparation') {
    git 'https://github.com/jglick/simple-maven-project-with-tests.git'
	sleep 3	  
   }
   stage('Compile') {
	echo 'I am from Compile Statge'
	sleep 3
   }
   stage('Testing') {
	echo 'I am from Testing Statge'
    sleep 3
   }
   stage('Deployment') {
	echo 'I am from Deployment Statge'
	sleep 3
   }
}
