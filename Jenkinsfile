node{
  stage('SCM Checkout') {
    git 'https://github.com/BibhuFourQ/jenkinsmaven/blob/master/Jenkinsfile'
  }
  stage('Compile-Package){
    sh 'mvn package'      
  }
 }
