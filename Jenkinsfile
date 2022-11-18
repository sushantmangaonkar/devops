pipeline {
    agent {
	      label {
		       label 'built-in'
		       customWorkspace '/mnt/slave-1'
		  
		  }
	}
    parameters {
        choice(name: 'choice', choice: 'testing-branch', description: 'this is a testing branch?')
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
