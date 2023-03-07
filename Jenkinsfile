def isPR = env.BRANCH_NAME.startsWith('PR')
node {
  stage("Checkout") {
     checkout scm 
  } 
  stage ("Build") {
    echo "Build Stage"
    echo "${isPR}"
    echo "PR branch Name ${env.BRANCH_NAME}"
    echo "Change Branch Name ${env.CHANGE_BRANCH}"
  }
}

