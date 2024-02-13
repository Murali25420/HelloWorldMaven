pipeline { 
    agent any 
    stages {
        stage('SCM') { 
            steps {
               git 'https://github.com/Murali25420/HelloWorldMaven.git'
                }
            }
            stage('Install'){
            steps {
                 sh "mvn Install"
	    }
	    }
	      stage('Compile'){
            steps {
                 sh "mvn Compile"
	    }
	      }
   stage('Test'){
            steps {
                 sh "mvn Test"
	    }
   }
	       stage('Package'){
            steps {
                 sh "mvn Package"
	    }
	       }
    }
}
