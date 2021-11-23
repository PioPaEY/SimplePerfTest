pipeline {
    agent {
        label 'jmeterslave'
    }

    stages {
        stage('Performance test') {
            steps {
                sh 'mvn clean verify'
            }
        }
    }
}