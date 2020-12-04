pipeline {
    agent any
      
    stages {
        stage('Build') {
            steps {
            sh '''
              ls
              pwd
              cd /home/cloud_user/chef-repo/
              ls
              echo "hola mundo"
            '''
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
