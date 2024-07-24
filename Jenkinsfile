pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "hi"
                sh '''#!/bin/bash
                 python3 test.py
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
