#!/usr/bin/env groovy

node {
    stage('checkout') {
        checkout scm
    }

    stage('check java') {
        sh "java -version"
    }
    stage('Test') {
	sh "sleep 5"	
    }

}
