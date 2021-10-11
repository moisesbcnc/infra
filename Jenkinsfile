pipeline {
    agent none

    stages {

        stage ('Config Repo') {
            agent any

            steps {
                echo 'prueba, '
                sh "hostname"

                sh '''#!/bin/bash
                    ip a
                    sh  /tmp/repo-exter.sh
                    mkdir /tmp/jenkinss
                    touch /tmp/infra
                    echo "Who 222 I'm $SHELL"
                '''
            }
        }
    }
}
