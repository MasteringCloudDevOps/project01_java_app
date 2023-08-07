@Library('my-shared-library@1.0') _

pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
                script {
                    gitCheckout(
                        branch: "main" ,
                        url: "https://github.com/MasteringCloudDevOps/project01_java_app.git"
                    )
                }
            }
        }
        stage('Unit Test Maven') {
            steps {
                script {
                    mvnTest()
                }
            }
        }
    }
}
