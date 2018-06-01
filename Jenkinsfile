#!groovy
node {
  stage 'Checkout'
    checkout scm

  stage 'Setup'
    sh 'npm install'

  stage 'Mocha    test'
    sh 'npm test'

  stage 'CleanUp and Prune'
    echo 'prune and cleanup'
    sh 'rm node_modules -rf'
}
