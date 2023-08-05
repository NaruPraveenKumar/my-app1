node{
  stage('checkout')
  {
  sh 'git clone https://github.com/NaruPraveenKumar/my-app1.git'
  }
  stage('buld')
  {
  def mvnHome = tool name: 'maven', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
  }
}
