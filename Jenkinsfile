node {

    stage('Gitclone'){
    
      git branch: 'main', credentialsId: '7269ef06-0c65-42d1-9d45-2f2147e32ea5', url: 'https://github.com/Nawazarifa/jenkinsproject12.git'
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
		  
		  
