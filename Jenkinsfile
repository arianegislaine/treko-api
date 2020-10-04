pipeline {
  agent{
    docker{
      image "node:8-alpine"
    }
  }
  stage{
    stage("build") {
      steps{
        sh "npm install"
      }
    }
  }
}
