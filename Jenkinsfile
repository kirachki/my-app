node {
   stage('SCM Checkout'){
     git 'https://github.com/kirachki/my-app.git' 
   }

   stage('Compile-Package'){
     def mvnHome = tool name: '', type: 'maven'
     sh "${mvnHome}/bin/mvn package"
   }

}
 
