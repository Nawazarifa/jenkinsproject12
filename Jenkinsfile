node {

    stage('Gitclone') {
	git branch: 'main', credentialsId: 'da1e8d01-80e2-477f-a0cd-a7d5a8605fd0', url: 'https://github.com/Nawazarifa/jenkinsproject12.git'
	    
	}
	stage('java version') {
	
	       sh 'java -version'
    }
	stage('maven version') {
	
	      sh 'mvn --version'
	}
	stage('maven validate ') {
	
	      sh  'mvn validate'
	}
	stage ('maven compile') {
	
	      sh  'mvn compile'
    }
	stage('maven test')  {
	
	      sh 'mvn test'
	}
	stage('maven package') {
	
	      sh 'mvn package'
	
	}
stage('maven deploy') {
	
	      sh 'mvn deploy'
	
	}
	}
		  
		  
