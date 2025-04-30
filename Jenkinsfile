pipeline {
    agent any
    options {
        checkoutToSubdirectory('src/main')
    }
    stages {
        stage('List Files') {
            steps {
                dir('src/main') {
                    sh 'ls -l'
                }
        }
    }
}

}
