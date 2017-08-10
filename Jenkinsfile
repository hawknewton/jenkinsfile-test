if(BRANCH_NAME == "master") {
  node {
      stage('Checkout') {
          git poll: true, url: 'git@github.com:hawknewton/jenkinsfile-test.git'
          print "MASTER!"
      }
  }
} else {
  node {
      stage('Checkout') {
          git poll: true, url: 'git@github.com:hawknewton/jenkinsfile-test.git'
          print "OTHER!"
      }
  }
}
