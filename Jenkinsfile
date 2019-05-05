pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Starting Build automation"
                sh './gradlew build'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
