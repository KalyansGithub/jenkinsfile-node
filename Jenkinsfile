node(){

  stage 'clone'
    checkout scm
  
  stage ' Env Details'
  //def branchName = "master"
   echo "My branch is: ${env.BRANCH_NAME}"

  if (env.BRANCH_NAME.equals("master")){
  echo "MASTER"
  }
  stage 'testing'

}
