pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Running Build kishore'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: './dist/tarinSchedule.zip'
      }
    }
  }
}
