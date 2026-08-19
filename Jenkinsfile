pipeline {
    agent any

    stages {

        stage('Git Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Test Jenkins') {
            steps {
                echo 'GitHub checkout successful!'
            }
        }
    }
}
