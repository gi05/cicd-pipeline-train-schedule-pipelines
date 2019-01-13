pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Buildind'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'

      }
    }
  }
}
