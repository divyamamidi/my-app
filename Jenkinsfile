pipeline {
    agent any
    stages {
        stage("Prepare") {
            steps {
                sh "git --version"
                script {
                    start_from = start_from_map["${START_FROM}"]
                }
            }
        }
    }
}