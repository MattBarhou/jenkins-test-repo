pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'master', url: 'https://github.com/MattBarhou/jenkins-test-repo'
            }
        }
        stage('Display Info') {
            steps {
                echo "Jenkins URL: ${JENKINS_URL}"
                echo "Build ID: ${BUILD_ID}"
            }
        }
    }
}
