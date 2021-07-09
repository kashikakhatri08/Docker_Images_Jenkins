pipeline {
    agent { 
        dockerfile {
            dir 'root'
            label 'master_label'
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
