pipeline {
    agent { docker { run '-it -d --network host --name fromjenkins debina' } }
    stages {
        stage('build') {
          steps {
                sh 'echo "testing"'
            }
        }
      }
   }
