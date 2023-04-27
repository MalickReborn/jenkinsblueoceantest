pipeline {
  agent any
  stages {
    stage('stage("Build")') {
      steps {
        sh '''if (isUnix()){sh \'/opt/maven/bin/mvn clean install\'}
'''
      }
    }

    stage('stage ("Test")') {
      steps {
        sh '''if (isUnix()){sh \'/opt/maven/bin/mvn clean test\'}
'''
      }
    }

  }
}