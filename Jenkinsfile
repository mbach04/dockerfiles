#!/usr/bin/env groovy
pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'which apache2'
            }
        }
    }
}