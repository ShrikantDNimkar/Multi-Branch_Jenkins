pipeline {
    agent any
    stages {
        stage('Branch') {
            steps {
                echo 'Hello branch1 '
            }
        }       
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
