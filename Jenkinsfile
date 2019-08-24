pipeline {
         agent any
          tools { 
        maven 'Maven 3.6.0' 
       
    }
         environment {
    PATH = "C:\\Program Files\\Git\\usr\\bin;C:\\Program Files\\Git\\bin;${env.PATH}"; 
         }
         stages {
                 stage('One') {
                 steps {
                                          bat 'mvn clean install'
                     }
                 }
         }
} 
