pipeline {
    agent {
        label 'ansible'
    }
    stages {
        stage('First') {
            steps {
                sh 'molecule test'
            }
        }           
    }
}