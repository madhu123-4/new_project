pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/madhu123-4/new_project'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the web page...'
                // Add build steps if necessary
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the web page...'
                // Add deployment steps if necessary
            }
        }
    }
}
