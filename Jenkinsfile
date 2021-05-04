peline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'echo "helloooooo!!!!"'
            }
        }
    }
    post {
        always {
            sh "echo 'dummy !!!'"
        }
    }
}
