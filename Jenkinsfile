pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Tamanna4373/maven-jenkins-pipeline.git'
            }
        }
        stage('Build') {
            steps {
                dir('YOUR_PROJECT_DIRECTORY') {  // Replace with your project directory name if it's in a subfolder
                    sh 'mvn clean install'
                }
            }
        }
    }
}
