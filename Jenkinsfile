node('master'){
  stage('SCM Checkout'){
    git 'https://github.com/elesela/my-app'
      }
      stage('Compile-package'){
        sh 'mvn install'
      }
}
