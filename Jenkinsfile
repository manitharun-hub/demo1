node{
  stage('Scm Checkout'){
  git 'https://github.com/manitharun-hub/demo1/'
  }
  stage('Compile-Pakage'){
  def svnHome = tool name: 'maven', type: 'maven'
    sh "${svnHome}/bin/maven pakage"
  }
}
