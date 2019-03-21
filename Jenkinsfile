node{
   stage('SCM Checkout'){
     git 'https://github.com/smuvw77/my-app'
   }
   stage('Compile-Package'){
    
      def mvnHome =  tool name: 'maven-3', type: 'maven'   
     

      sh "${mvnHome}/bin/mvn package"
   }
  
 }
