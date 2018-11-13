pipeline {
  agent none
  stages {
    stage('build') {
      steps {
        build(job: 'build', propagate: true, wait: true)
      }
    }
  }
}