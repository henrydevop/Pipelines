pipeline {
    agent any

    environment {
        PROJECT_NAME = "Neptun"
        OWNER_NAME = "Junior"
    }

    stages {
        stage('1-Build') {
            steps {
                echo 'Start of Stage Build'
                sh '''
                    ls -la .
                    echo '123'
                '''
                echo 'Building.....'
                echo 'End of Stage Build'
            }
        }
        stage('2-Test') {
            steps {
                echo 'Start of Stage Test'
                echo 'Testing.....'
                echo "Hello ${OWNER_NAME}"
                echo "Hello Project name is ${PROJECT_NAME}"
                echo "End of Stage Test"
            }
        }
        stage('3-Deploy') {
            steps {
                echo 'Start of Stage Deploy'
                echo 'Deploying.....'
                echo 'Start of Stage Deploy'
            }
        }
    }
}

