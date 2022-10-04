pipeline {
    agent { label 'label' }

    stages {

        stage ('Build') {
            agent { label 'label' }

            steps {
                sh '''apt update
                apt install build-essential
                make'''
            }
        }
    }
}