node {

    stage('Gitclone') {
	
	    git branch: 'main', credentialsId: '06bb3d20-bbaf-4add-a6c1-903bacb34d82', url: 'https://github.com/Nawazarifa/Arifa.git'
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
		  
		  
