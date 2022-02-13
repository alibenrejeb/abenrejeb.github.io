pipeline {
    agent { docker { image 'maven:3.8.4-openjdk-11-slim' } }
    tools {nodejs "nodejs"}
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'npm run sass'
            }
        }
    }
}
