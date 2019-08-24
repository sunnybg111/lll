pipeline {
    agent any
    environment {
    PATH = "C:\\Program Files\\Git\\usr\\bin;C:\\Program Files\\Git\\bin;${env.PATH}"
    stages {
   
        stage('Example') {
            steps { 
                sh 'mvn clean install'
            }
        }
        }
    }
}
