pipeline {
  agent any
  stages{
    stage('Build'){
      steps{
        echo "Building Project"
      }
      stage('Archive'){
        steps{
          echo "Archive Project"
      }
      stage('Build Docker Image'){
        steps{
          echo "Building Docker Image"
      }
      stage('Push Docker Image'){
        steps{
          echo "Pushing Docker Imaget"
      }
      stage('Deploy to Dev'){
        steps{
          echo "Deploying to Dev Environment"
      }
    }
  }
}
