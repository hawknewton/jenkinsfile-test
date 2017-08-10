node {
    stage('Checkout') {
        git poll: true, url: 'git@github.com:hawknewton/jenkinsfile-test.git'
        echo "Current branch is ${env.GIT_BRANCH}"
        print "Current branch is ${BRANCH_NAME}"
    }
}
