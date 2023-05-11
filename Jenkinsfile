pipeline {
    agent { label 'aspen-staging-permanent' }
    stages {
        stage('Pull the repo') {
            steps {
                dir('/home/aspen2022/testJenkins') {
                    checkout scm
                }
            }
        }
    }
}
