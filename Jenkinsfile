pipeline {
    // agent {
    //     docker { image 'node:7-alpine' }
    // }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'docker version'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}