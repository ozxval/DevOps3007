properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
  stage("clone"){
    git "https://github/ozxval/DevOps3007.git"
  }
  stage("show file"){
    dir
  }
}
