pipeline{
  agent any
  stages{
    stage("checkout"){
      when{
        branch "develop"
      }
      steps{
        echo "Git checkout successful"
      }
    }
    stage("maven build"){
      when{
        branch "test"
      }
      steps{
        echo "maven build is successful"
      }
    }
    stage("tomcat deployment"){
      when{
        branch "main"
      }
      steps{
        echo "Tomcat deployment successful"
      }
    }
  } 
  }
