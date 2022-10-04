pipeline {
    agent none

    stages {

        stage ('Build') {
            agent any

            steps {
                sh '''apt update
                apt install build-essential
                make'''
            }
        }
    }
}