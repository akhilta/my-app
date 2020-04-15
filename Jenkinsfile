node{
  stage('SCM Checkout'){
   
    git 'https://github.com/akhilta/my-app.git'
  }
  stage('Compile-Package'){
    if (isUnix()) --> sh "mvn package"
     else --> bat "mvn package"

  }
}
