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
                    mkdir /tmp/jenkins1
                    echo "Who 222 I'm $SHELL"
                '''
            }
        }
    }
}
