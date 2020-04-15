node{
  stage('SCM Checkout'){
   
    git 'https://github.com/akhilta/my-app.git'
  }
  stage('Compile-Package'){
    def mvnhome= tool name:'m1',type: 'maven'
    sh mvn package"
  sh 'mvn package'
  }
}
