pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'cat /etc/os-version'
                sh 'mvn --version'
            }
        }
    }
}
