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
        
        stage('Publish') {
            steps {
                bat 'C:/Users/sqwjng/Desktop/Jenkins/Day2/publish.bat'
            }
        }
        
    }
}
