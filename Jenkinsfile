pipeline { 
    agent any 
    stages {
        stage('Install') { 
            steps {
               sh "mvn install "
                }
            }
            stage('Test'){
            steps {
                 sh "mvn test"
	    }
	    }
    }
}
