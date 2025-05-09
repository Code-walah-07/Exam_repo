pipeline {
    agent any  

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
            
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'

            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
          
            }
        }
    }

    post {
        always {
            echo 'This will always run after the pipeline finishes, regardless of success or failure.'
        }

        success {
            echo 'This runs when the pipeline is successful.'
        }

        failure {
            echo 'This runs if the pipeline fails.'
        }
    }
}
