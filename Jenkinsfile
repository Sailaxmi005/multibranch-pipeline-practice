pipeline {
    agent any

    stages {
        stage('Testing') {
            when{
                branch 'testing'
            }
            steps {
                echo 'Hello World testing'
            }
        }
        stage('Main') {
            when{
                branch 'main'
            }
            steps {
                echo 'Hello World Main'
            }
        }
    }
}
