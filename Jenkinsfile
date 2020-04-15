node{
  stage('SCM Checkout'){
   
    git 'https://github.com/akhilta/my-app.git'
  }
  stage('Compile-Package'){
    def mvnhome= tool name:'m1',type: 'maven'
    sh "${mvnhome}/bin/mvn package"
  sh 'mvn package'
  }
}
