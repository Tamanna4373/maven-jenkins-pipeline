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
                sh 'mvn clean install'
            }
        }
    }
}
