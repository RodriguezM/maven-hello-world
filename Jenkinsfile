pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'cd my-app'
                bat 'dir'
                bat 'cd my-app'
                bat 'dir'
            }
        }
    }
}
