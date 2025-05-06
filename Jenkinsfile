pipeline {
    agent {
        docker {
            image 'maven:3.8.5-openjdk-17' // Or any other Maven image
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}

