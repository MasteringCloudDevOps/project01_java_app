pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
                script {
                    git branch: 'main', url: 'https://github.com/MasteringCloudDevOps/project01_java_app.git'
                }
            }
        }
    }
}
