pipeline {
    agent any
    stages { 
        stage('Build Project') {
            steps {
                echo 'Building Project'
              
            }
        }
      stage('Archive  Project') {
            steps {
                echo 'Archiveing Project'
               
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
