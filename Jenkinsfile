#!groovy
node {
  stage 'Checkout'
    checkout scm

  stage 'Setup dis'
    sh 'npm install'

  stage 'Mocha    test'
    sh 'npm test'

  stage 'Cleanup and Prune'
    echo 'prune and cleanup'
    sh 'rm node_modules -rf'
}
