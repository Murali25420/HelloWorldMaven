pipeline { 
    agent any 
    stages {
        stage('SCM') { 
            steps {
               git 'https://github.com/Murali25420/HelloWorldMaven.git'
                }
            }
            stage('install'){
            steps {
                 sh "mvn install"
	    }
	    }
	      stage('compile'){
            steps {
                 sh "mvn compile"
	    }
	      }
   stage('test'){
            steps {
                 sh "mvn test"
	    }
   }
	       stage('package'){
            steps {
                 sh "mvn package"
	    }
	       }
    }
}
