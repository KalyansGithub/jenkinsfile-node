node(){

  stage 'clone'
    checkout scm
  
  stage ' Env Details'
  //def branchName = "master"
   echo  "branch name is ${env.BRANCH_NAME}"

  if ("${env.BRANCH_NAME}".equals("master")){
  echo "MASTER"
  }
  stage 'testing'

}
