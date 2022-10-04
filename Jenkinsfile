pipeline {
    agent any
    stages {   
        stage ('build') {
            steps {
                sh 'mvn clean package'
            }
        }

        stage ('test') {
            steps {
                echo 'testing'
            }
        }

        stage ('deploy') {
	        steps {
		     sh 'chmod 777 ${WORKSPACE}/target/OpsWays-0.0.1-SNAPSHOT.jar'
 	 
		 }
         }
   }
}
