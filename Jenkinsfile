pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('Build') {
            steps{
                echo 'Committed successfully'
                sh '/opt/node-v12.16.1-linux-x64/bin/npm install'
            }

        }

    }
}
