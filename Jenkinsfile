pipeline {
    agent {
        docker { image 'ubuntu:latest' }
    }
}
    stages {
        stage('Build') { 
            steps {
                sh 'lsb_release -a' 
            }
        }
    }
}
