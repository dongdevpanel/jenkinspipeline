node {
  stage('Checkout')
  {
    checkout scm
  }
  stage('Build')
  {
    echo "Building the Project"
    sh 'cat test'
    sh 'echo test > ~/test.txt'
    sh 'cat ~/test.txt'
  }
  stage('Deploy')
  {
    echo "Deploying the Project"
  }
  stage('Test')
  {
    echo "Testing"
  }
  stage('Release')
  {
    echo "Releasing the Project"
  }
}
