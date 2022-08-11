properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
  stage("clone"){
    git "https://github.com/ozxval/DevOps3007.git"
  }
  stage("show file"){
    dir
  }
}
