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
         stage('Deploy'){
                steps{
                    echo "Not really deploying anything"
                }
            }
    }
}
