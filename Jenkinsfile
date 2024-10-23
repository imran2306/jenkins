pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo "BUILD_ID = ${env.BUILD_ID}"
                echo "JENKINS_URL = ${env.JENKINS_URL}"
                echo "BUILD_NUMBER = ${env.BUILD_NUMBER}"
                echo "JOB_NAME = ${env.JOB_NAME}"
                echo "WORKSPACE = ${env.WORKSPACE}"
                echo "BRANCH_NAME = ${env.BRANCH_NAME}"
                echo "GIT_COMMIT = ${env.GIT_COMMIT}"
            }
        }
    }
}
