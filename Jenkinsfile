#!groovy
node {
  stage 'Checkout'
    checkout scm

  stage 'Setup'
    sh 'npm install'
    sh 'asss'

  stage 'Mocha test'
    sh './node_modules/mocha/bin/mocha'

  stage 'Cleanup'
    echo 'prune and cleanup'
    sh 'rm node_modules -rf'
}


