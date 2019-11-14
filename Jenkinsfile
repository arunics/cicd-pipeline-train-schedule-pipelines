pipeline {
  agent any
  stages {
    stage ('Name') {
      steps {
        echo "Hola"
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: dist/trainSchedule.zip
      }
    }
    
  }
}
