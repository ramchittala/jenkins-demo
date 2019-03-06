  node{
   stage('SCM Checkout'){
     git 'https://github.com/ramchittala/jenkins-demo'
   }
   stage('Compile-Package'){
    
      def mvnHome =  tool name: 'M3', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   }
   
}


