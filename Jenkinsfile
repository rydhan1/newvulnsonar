pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                
         sh '''#!/bin/bash
                 mvn deploy
         '''
                
            }
        }
        stage('Test') {
            steps {
                 echo 'Test....'
            }
        }
        stage('Super test') {
            steps {
                 echo 'Super Test....'
            }
        }
    }
}
