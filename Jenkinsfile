//node('master'){
 // stage('SCM Checkout'){
   // git 'https://github.com/elesela/my-app'
   //   }
    //  stage('Compile-package'){
     //   sh 'mvn install'
    //  }
//}
node{
  stage('checkout code')
  {
    stage('Build'){
      bat 'cd multibranch-pipeline-by-pknowledge & mvn clean install -U'
    }
  }
}
