pipeline {
    agent {
        node { label 'workstation' }
    }

    stages {
        stage('Hello DevOps') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post {
      always {
        echo 'I will always say Hello again!'
      }
    }
}