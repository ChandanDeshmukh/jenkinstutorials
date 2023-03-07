node {
  stage("Checkout") {
     checkout scm 
  } 
  stage ("Build") {
   if (env.BRANCH_NAME.startsWith('PR')) {
    echo "Build Stage"
    echo "${env.BRANCH_NAME}"
    echo "${env.CHANGE_BRANCH}"
   }
   
  }
}

