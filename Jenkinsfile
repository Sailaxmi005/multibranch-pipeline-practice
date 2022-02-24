pipeline {
    agent any

    stages {
        stage('Testing') {
            when{
                branch 'testing'
            }
            steps {
                  script{
                 
                    git 'https://github.com/Sailaxmi005/MULTIBRANCH-PIPELINE.git'
                    
                }
                echo 'Hello World testing'
            }
        }
        stage('Main') {
            when{
                branch 'main'
            }
            steps {
                  script{
                 
                    git 'https://github.com/Sailaxmi005/MULTIBRANCH-PIPELINE.git'
                    
                }
                echo 'Hello World Main'
            }
        }
    }
}
