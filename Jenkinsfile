pipeline {
    agent any

    stages {
        stage('Package') {
            steps {
                
         sh '''#!/bin/bash
                 mvn package
         '''
                
            }
        }
        stage('Deploy') {
            steps {
                 sh '''#!/bin/bash
                 mvn deploy
         '''
            }
        }
        stage('Confirm') {
            steps {
                echo 'Confirming....'
            }
        }
    }
}
