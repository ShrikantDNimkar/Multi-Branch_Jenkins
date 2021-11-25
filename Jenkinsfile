pipeline {
    agent any
    stages {
        stage('Branch') {
            steps {
                echo 'Hello Bug branch '
            }
        }       
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
