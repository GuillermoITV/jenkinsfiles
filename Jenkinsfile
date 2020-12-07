pipeline {
    agent { label 'nodo1' }
    stages {
        stage('Build') {
            steps {
                echo 'Hola 2'
                sh '''
                  #!/bin/bash
                  ls
                  pwd
                  uname -a
                  ls
                '''
            }
        }
    }
}
