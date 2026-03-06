pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Pipeline is running'
            }
        }

        stage('Maven Build') {
            steps {
                sh 'mvn compile'
            }
        }

    }
}
