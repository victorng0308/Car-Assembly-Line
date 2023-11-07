pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
            bat 'C:/Users/sqwjng/Desktop/Jenkins/Day2/build.bat'
            }
        }
        
        stage('Test') {
            steps {
                bat 'C:/Users/sqwjng/Desktop/Jenkins/Day2/test.bat'
            }
        }
        
        stage('Package') {
            steps {
                bat 'C:/Users/sqwjng/Desktop/Jenkins/Day2/package.bat'
            }
        }

         stage('Deploy') {
            steps {
                bat 'C:/Users/sqwjng/Desktop/Jenkins/Day2/deploy.bat'
            }
        }
        
    }
}
