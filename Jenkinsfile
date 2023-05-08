pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Build'
            }
        }
         stage('build') {
            steps {
                echo 'Test'
            }
        }
         stage('test') {
            steps {
                echo 'DEPLOY'
            }
        }
         stage('deploy') {
            steps {
                echo 'Image step'
            }
        }
    }
}
