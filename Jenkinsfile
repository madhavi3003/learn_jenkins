pipeline {
    agent {
    node {
        label 'Jenkins_agent'
    }
}

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh """
                  pwd
                  ls -l
                  
                """
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
