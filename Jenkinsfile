
pipeline {
    agent any
    stages{
        stage('Build'){
            steps{
                echo 'Create Build Artifact'
            }
        }
        stage('Package'){
            steps{
                echo 'Move Artifact to Build Repository'
            }
        }
        stage('Deploy'){
            steps{
                echo 'Push the artifact to an environment'
            }
        }
    }
}
