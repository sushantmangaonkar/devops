pipeline {
    agent {
	      label {
		       label 'built-in'
		       customWorkspace '/mnt/slave-1'
		  
		  }
	}
    parameters {
        choice(name: 'choice',  choices: ['master-branch'], description: 'this is a testing branch?')
    }
    stages {
        stage('master-branch') {
            steps {
                echo "devlope code ${params.choice}"

                echo "updated code in master branch"

            
            }
        }
    }
}
