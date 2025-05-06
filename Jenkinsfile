pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // This ensures Jenkins clones the repo properly
                checkout scm
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
