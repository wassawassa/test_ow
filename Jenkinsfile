pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo "build stage."'
            }
        }
        stage('test') {
            steps {
                sh 'echo "test stage."'
            }
        }
    }
    post {
        always {
            echo 'always run.'
        }
        success {
            echo 'this messages is shown only if succeeded jobs.'
        }
    }
}
