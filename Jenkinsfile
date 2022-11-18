pipeline {
    agent {
	      label{
		       label 'built-in'
		       customWorkspace '/mnt/slave-1'
		  
		  }
	}
    parameters {
        string(name: 'choice', defaultValue: 'devlopment-branch', description: 'this is a dev branch?')
    }
    stages {
        stage('dev-branch') {
            steps {
                echo "devlope code ${params.choice}"

                echo "code devlopment is sucessfully done"

            
            }
        }
    }
}
