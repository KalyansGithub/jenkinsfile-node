node(){

  stage 'clone'
    checkout scm
  
  stage ' Env Details'
  //def branchName = "master"
  if (env.BRANCH_NAME.equals("master")){
  echo "MASTER"
  }
  stage 'testing'

}
