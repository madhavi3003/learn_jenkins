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
                  pwd
                  
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
