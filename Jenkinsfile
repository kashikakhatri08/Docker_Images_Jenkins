pipeline {
    agent { 
        dockerfile {
            dir 'root'
            label 'master_label'
            args  '-v /tmp:/tmp'
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
