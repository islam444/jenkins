pipeline {
    agent { label 'label' }

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