pipeline{
    agent any 
    
    stages{
        stage('Git Checkout'){
            steps{
                Script
                    git branch: 'main', url: 'https://github.com/krishbeck/mrdevops_java_app.git'
            }
        }
    }
}