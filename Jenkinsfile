pipeline {
    agent { 
        dockerfile {
            dir 'root'    
        } 
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
