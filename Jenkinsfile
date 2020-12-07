pipeline {
    agent { label 'nodo2' }
    stages {
        stage('Build') {
            steps {
                echo 'Hola 3'
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
