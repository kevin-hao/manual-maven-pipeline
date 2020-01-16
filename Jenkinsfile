#!/usr/bin/env groovy

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "printenv"
                sh "mvn clean test package spring-boot:repackage"

            }
        }
    }
}