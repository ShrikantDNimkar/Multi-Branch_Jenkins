pipeline {
    agent any
    stages {
        stage('Branch') {
            steps {
                echo 'Hello Future branch '
            }
        }       
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
