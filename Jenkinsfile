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
                 echo 'Middle....'
            }
        }
        stage('Confirm') {
            steps {
                 sh '''#!/bin/bash
                 mvn deploy
                 '''
            }
        }
    }
}
