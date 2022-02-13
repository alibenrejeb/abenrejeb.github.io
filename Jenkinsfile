pipeline {
    agent { docker { image 'jimador/docker-jdk-8-maven-node' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'npm run sass'
            }
        }
    }
}
