pipeline {
    agent { label 'nodo1' }
    stages {
        stage('Build') {
            steps {
                echo 'Hola'
                sh '''
                  #!/bin/bash
                  uname -a
                  pwd
                  ls
                '''
            }
        }
    }
}
