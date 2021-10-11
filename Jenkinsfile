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
                    cd /home/ec2-user/infra && sudo git pull
                    sh  /tmp/repo-exter.sh
                    mkdir /tmp/jenkinss
                    touch /tmp/infra
                    echo "Who 222 I'm $SHELL"
                '''
            }
        }
    }
}
