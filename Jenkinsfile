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
		     sh 'echo helloworld'
 	 
		 }
         }
   }
}
