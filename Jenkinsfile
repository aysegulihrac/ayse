pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Clarusway_Way to Reinvent Yourself"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
    stages {
        stage("run") {
            steps {
                echo "hello clarusway"
                sh "python python.py"
                sh "python --version"
            }
        }    
    }
}
