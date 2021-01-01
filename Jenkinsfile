pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('Build') {
            steps{
                echo 'Committed successfully'
            }
            steps{
                sh 'npm install'
            }
        }
    }
}
