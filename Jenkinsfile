pipeline {
    agent any
    
    stages{
        stage('Build'){
            steps {
                echo 'Hello World'
            }
            post {
                success {
                    echo 'Now Archiving...'
                    
                }
            }
        }
    }
}
