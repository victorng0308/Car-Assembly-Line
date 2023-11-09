pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            bat 'C:/Users/sqwjng/Desktop/Jenkins/Day2/build.bat'
          }
        }

        stage('Print') {
          steps {
            echo 'Build'
          }
        }

      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            bat 'C:/Users/sqwjng/Desktop/Jenkins/Day2/test.bat'
          }
        }

        stage('Print') {
          steps {
            echo 'Test'
          }
        }

      }
    }

    stage('Package') {
      parallel {
        stage('Package') {
          steps {
            bat 'C:/Users/sqwjng/Desktop/Jenkins/Day2/package.bat'
          }
        }

        stage('Print') {
          steps {
            echo 'Package'
          }
        }

      }
    }

    stage('Deploy') {
      parallel {
        stage('Deploy') {
          steps {
            bat 'C:/Users/sqwjng/Desktop/Jenkins/Day2/deploy.bat'
          }
        }

        stage('Print') {
          steps {
            echo 'Deploy redo'
          }
        }

      }
    }

  }
}