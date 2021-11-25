pipeline {
    agent any
    stages {
        stage('Branch') {
            steps {
                echo 'Hello Main branch '
            }
        }       
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
