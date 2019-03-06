  pipeline {
    agent any
 stages
    {
    stage('SCM Checkout'){
      steps
      {
     git 'https://github.com/ramchittala/jenkins-demo'
      }
    }

    stage('Compile-Package'){
    steps{
           sh 'mvn package'
    }
    }
    
  }
   
}


