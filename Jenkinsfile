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
            }
        }
        
         stage('deployment') {
            steps {
                sh 'mvn deploy'
            }
        }
    }
}
