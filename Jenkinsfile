pipeline {
    agent any
    stages {
        stage('Hello1') {
            steps {
                git 'https://github.com/Vidhu-1997/hello-world.git'
            }
        }
        
        stage('compile11') {
            steps {
                sh 'mvn clean package'
				echo 'deployment success'
            }
        }
        
        stage('deployment') {
			steps {
                echo 'deployment success'
            }
        }
		stage('docker') {
			steps {
                echo 'docker'
            }
        }
		stage('ansible') {
			steps {
                echo 'ansible'
            }
        }
		stage('docker image') {
			steps {
                echo 'docker image'
            }
        }
		stage('docker containerization') {
			steps {
                echo 'docker containerization'
            }
        }
		stage('docker deployment') {
			steps {
                echo 'docker deployment'
            }
        }
		stage('ansible automation') {
			steps {
                echo 'ansible automation'
            }
        }
		stage('ansible deployment') {
			steps {
                echo 'ansible deployment'
            }
        }
		stage('kubernetes') {
			steps {
                echo 'kubernetes'
            }
        }
		stage('kubernetes deployment') {
			steps {
                echo 'kubernetes deployment'
            }
        }
		stage('artifacts') {
			steps {
                echo 'artifacts'
            }
        }
		stage('live environment') {
			steps {
                echo 'live environment'
            }
        }
		stage('live deployment') {
			steps {
                echo 'deployment success'
            }
        }
		stage('prod deployment') {
			steps {
                echo 'prod deployment'
            }
        }
    }
}
