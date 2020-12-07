pipeline {
    agent { label 'nodo2' }
    stages {
        stage('Build') {
            steps {
                echo 'Hola 2'
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
