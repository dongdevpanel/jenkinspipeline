node {
  stage('Build')
  {
    checkout scm
    echo "Building the Project"
    sh 'cat test'
    sh 'echo test > ~/test.txt'
    sh 'cat ~/test.txt'
  }
  stage('Deploy')
  {
    echo "Deploying the Project"
  }
  stage('Release')
  {
    echo "Releasing the Project"
  }
}
