node {
   stage('SCM Checkout'){
     git 'https://github.com/kirachki/my-app.git' 
   }

   stage('Compile-Package'){
	   sh "mvn package"
   }

}
