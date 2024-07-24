pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "hi"
                sh '''#!/bin/bash
                 touch /tmp/bb.txt
                '''
            }
        }
        stage('Test') { 
            steps {
            echo "hii"
            }
        }
        stage('Deploy') { 
            steps {
                echo "hiii"
            }
        }
    }
}
