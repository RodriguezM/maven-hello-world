pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                dir('my-app') {
                    bat 'mvn compile'
                    bat 'java -cp target/classes com.mycompany.app.App'
                }
            }
        }
    }
}
