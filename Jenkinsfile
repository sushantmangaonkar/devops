pipeline {
    agent {
	      label {
		       label 'built-in'
		       customWorkspace '/mnt/slave-1'
		  
		  }
	}
    parameters {
        string(name: 'choice', defaultValue: 'software-branch', description: 'this is a software branch?')
    }
    stages {
        stage('soft-branch') {
            steps {
                echo "software branch ${params.choice}"

                echo "code in software branch"

            
            }
        }
    }
}
