pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                cd my-app
                mvn compile
                java -cp target/classes com.mycompany.app.App
            }
        }
    }
}
