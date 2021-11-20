pipeline {
  
  agent { docker { image 'python:3.5.1' } }
  
  stages {
    
    stage("build") {
      
      steps {
        echo 'building the application...'
      }
    }
    
    stage("test") {
      
      steps {
        sh 'python --version'
      }
    }
    
    stage("deploy") {
      
      steps {
        echo 'deploying the application...'        
      }
    }
  }
}
