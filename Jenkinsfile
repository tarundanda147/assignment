@Library("my_shared_library") _

pipeline {
  agent { label 'java' }
        stages {
          stage("print_hello") {
          steps {
            helloworld()
          }
       }
            stage("print_goodnight") {
            steps {
            goodnight()
            }
         }
      }
 }
