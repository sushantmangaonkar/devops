pipeline {
    agent {
	      label{
		       label 'built-in'
		       customWorkspace '/mnt/slave-1'
		  
		  }
	}
    parameters {
        choice(name: 'choice', choices: ['development-branch]', description: 'this is a dev branch?')
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
