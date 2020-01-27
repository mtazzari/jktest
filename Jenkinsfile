pipeline {
  agent any
  stages {
    stage('Hello') {
      parallel {
        stage('Hello') {
          steps {
            sh '''echo \'Hello world!\'

'''
          }
        }

        stage('Touch file') {
          steps {
            sh '''touch /data/test.txt
'''
          }
        }

      }
    }

  }
}