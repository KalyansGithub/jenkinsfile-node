node(){

  stage 'clone'
    checkout scm
  
  stage ' Env Details'
  //def branchName = "master"
  echo  "Branch name is :${env.JOB_NAME}"

  if ("${env.BRANCH_NAME}".equals("master")){
  echo "MASTER"
  }
  stage 'testing'

}
