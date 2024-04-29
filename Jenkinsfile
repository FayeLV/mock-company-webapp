pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Build
                sh './gradlew assemble'
            }
        }
        stage('Test') {
            steps {
                // Test
                sh './gradlew test'
            }
        }
    }
}
