pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
               echo 'wie gehts dir freddy ?'
          sh './gradlew build --no-deamon'   
            archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
        stage('Deploy') {
        
        }
    }
}
