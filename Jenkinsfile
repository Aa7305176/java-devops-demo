pipeline {
    agent any
  
    stages {
        echo 'this is master branch'
        stage('build') {
            steps {
                echo '111'
            }
        }
  
    stage('Test'){
            steps {
                echo '222'
            }
        }
        
    stage('Deploy') {
            steps {
                echo '333'
            }
        }
    }
}
