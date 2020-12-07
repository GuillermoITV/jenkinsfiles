pipeline {
    agent { label 'nodo2' }
    stages {
        stage('Build') {
            steps {
                echo 'esto lo ejecutaria en el nodo 3... si al menos tuviera uno!!!'
                sh '''
                  ls
                  pwd
                  uname -a
                  ls
                '''
            }
        }
    }
}
