pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'cd my-app'
                bat 'mvn clean install'
                bat ''
            }
        }
    }
}
