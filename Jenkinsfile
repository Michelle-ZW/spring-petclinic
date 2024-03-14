pipeline {
  agent any
  triggers {
  cron 'H/10 * * * 4'
}
  stages {
    stage('JaCoCo Stage') {
      steps {
        jacoco()
      }
    }

  }
}
