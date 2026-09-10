pipeline {
    agent any

    environment {
        APP_NAME = 'demo'
    }

    stages {
        stage('Build') {
            environment {
                BUILD_MODE = 'Production'
            }

            steps {
                sh 'echo $APP_NAME $BUILD_MODE'
            }
        }

        stage('Test') {
            steps {
                sh 'echo $APP_NAME'
            }
        }
    }
}
