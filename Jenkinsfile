pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                echo 'this is build'
                python '/var/lib/jenkins/workspace/TestNew/dbchk.py'
		sh "/usr/bin/python /var/lib/jenkins/workspace/TestNew/dbchk.py"
            }
        }
        stage('Test'){
            steps {
                echo 'this is test'
				
                
            }
        }
        stage('Deploy') {
            steps {
                echo 'this is deploy'
	
				
				
				
            }
        }
    }
}