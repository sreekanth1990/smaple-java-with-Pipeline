pipeline {
    agent any 
    tools { 
        maven 'Maven 3.3.9' 
           }
    stages {
        stage('Build') { 
            steps {
                sh 'date'
                sh 'whereis mvn'
                 sh 'mvn -Dmaven.test.failure.ignore=true install' 
            }
        }
        stage('Test') { 
            steps {
            sh 'date'
                            }
        }
        stage('Deploy') { 
            steps {
               sh 'date'
            }
        }
    }
}
