pipeline {
    agent any
    tools {
     maven 'MAVEN'
    }

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/bhanumannurultts/hello-world.git'
            }
        }
        
        stage('compile') {
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
    }
}
