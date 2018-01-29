pipeline {
  agent none
  stages {
    stage('Maven Build') {
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }
  }
}