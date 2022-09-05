node{
  stage('SCM Checkout'){
    git 'https://github.com/altafrs77/ValaxyTech-hello-world'  
  }
  stage('Compile Package'){
    def mvn_path = tool name: 'M2_HOME', type: 'maven'
    sh "${mvn_path}/bin/mvn package"
  }
}
