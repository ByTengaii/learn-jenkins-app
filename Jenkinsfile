pipeline{
    agent any

    stages{
        stage('Hello') {
            steps {
                script {
                    echo 'Hellp.'
                    // Add your build commands here
                }
            }
        }
        stage('Build') {
            steps {
                script {
                    echo 'Building...'
                    // Add your build commands here
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    echo 'Testing...'
                    // Add your test commands here
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    echo 'Deploying...'
                    // Add your deploy commands here
                }
            }
        }
    }
}