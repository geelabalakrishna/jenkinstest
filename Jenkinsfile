pipeline {
    agent any
    options {
        checkoutToSubdirectory('src/main')
    }
    stages {
        stage('List Files') {
            steps {
                    sh 'ls -la'

            }
        }
    }
}
