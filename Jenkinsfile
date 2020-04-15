node{
  stage('SCM Checkout'){
   
    git 'https://github.com/akhilta/my-app.git'
  }
  stage('Compile-Package'){
     bat "mvn package"
    java -cp C:\Program Files (x86)\Jenkins\workspace\jenkins-pipeline\target\my-app-1.0-SNAPSHOT.jar com.mycompany.app
  }
}
