node {
    stage('Checkout') {
        git poll: false, url: 'git@github.com:hawknewton/jenkinsfile-test.git'
        echo "Current branch is ${env.GIT_BRANCH}"
    }
}
