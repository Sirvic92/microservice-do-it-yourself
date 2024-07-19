pipeline {
    agent any
    triggers {
        githubPush() // Adding the githubPush trigger to trigger the pipeline on GitHub push events
}
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        

        
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }


    }
}