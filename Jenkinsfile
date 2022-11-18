pipeline {
    agent {
	      label{
		       label 'linux'
		       customWorkspace '/mnt/slave-1'
		  
		  }
	}
    parameters {
        string(name: 'choice', defaultValue: 'testing-branch', description: 'this is a testing branch?')
    }
    stages {
        stage('test-branch') {
            steps {
                echo "devlope code ${params.choice}"

                echo "code testing is sucessfully done"

            
            }
        }
    }
}
