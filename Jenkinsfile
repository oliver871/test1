pipeline {
    agent any
 /*       docker {
            image 'jenkins/jenkins:lts'
            args '-p 3000:3000'
        }
    }
*/
    stages {
        stage('Build') {
            steps {
                bat 'npm install'
            }
        }
    }
}