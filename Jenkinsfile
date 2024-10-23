pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo '''
                BUILD_ID = ${env.BUILD_ID}
                JENKINS_URL =  ${env.JENKINS_URL}
                '''
            }
        }
    }
}
