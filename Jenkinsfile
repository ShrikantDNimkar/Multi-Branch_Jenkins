pipeline {
    agent any
    stages {
        stage('Branch') {
            steps {
                echo 'Hello branch2 '
            }
        }       
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
