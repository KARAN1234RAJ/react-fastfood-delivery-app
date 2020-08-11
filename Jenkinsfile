pipeline {
    agent any
    stages { 
        stage('Build Project') {
            steps {
                echo 'Building Project'
                sh 'npm install'
            }
        }
      stage('Archive  Project') {
            steps {
                echo 'Archiveing Project'
                archiveArtifacts artifacts: '**/*.jar', followSymlinks: false
            }
        }
      stage('Build Docker Image') {
            steps {
                echo 'Building Docker Image'
            }
        }
      stage('Push Docker Image') {
            steps {
                echo 'Pushing Docker Image'
            }
        }
      stage('Deploy to Dev') {
            steps {
                echo 'Deploying to Dev Environment'
            }
        }
    }
  
}
