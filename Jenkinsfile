pipeline {
    options {
        ansiColor('xterm')
    }
    agent {
        dockerfile {
        filename 'Dockerfile'
        }
    }

    stages {
        stage('Cleanup S3') {
            options {
                ansiColor('xterm')
                withAWS(role:'mgmt_jenkins', roleAccount:'146708650527')
            }
            steps {
                sh 'echo put your script here'
            }
        }
}