pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3000:3000'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                //echo 'Running build automation'
                //sh './gradlew build --no-daemon'
                //archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
        stage('Prod') {
            steps {
               // echo 'Running build automation'
               // sh './gradlew build --no-daemon'
               // archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
