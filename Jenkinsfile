@Library("my_shared_library") _

pipeline {
  agent {label 'java'}
  stages{
    stage('checkout') {
      steps {
        sh 'rm -rf hello-world-war'
        sh 'git clone https://github.com/tarundanda147/hello-world-war/'
        ls
      }
    }
    stage('Build') {
            steps {
                script {
                    ls
                    build()
        }
      }
    }
  }
}
