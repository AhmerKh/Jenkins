pipeline {
    agent { docker { image 'node:20.10.0-alpine3.19' } }
    stages {
        stage('build') {
            steps {
                dir('C:/ProgramData/Jenkins/containers')
                sh 'node --version'
            }
        }
    }
}
