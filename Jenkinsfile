node {
  stage("Checkout") {
     checkout scm 
  }
  stage ("Build") {
    echo "Build Stage"
    echo "${env.BRANCH_NAME}"
  }
}

