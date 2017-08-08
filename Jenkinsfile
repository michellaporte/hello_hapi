#!/usr/bin/env groovy

pipeline {

    agent {
        docker {
            image 'ubuntu'
            args '/bin/bash'
        }
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'apt-get update'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'apt-get update'
            }
        }
    }
}
