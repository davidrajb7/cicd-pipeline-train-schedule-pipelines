pipeline {
  agent any
  stages {
    stage("Build") {
    Steps {
    echo " Running build automation"
    sh."/gradlew.build--no-demon"
    archiveArtifacts artifacts: 'dist:trainSched'
    }
    }
  }

}
