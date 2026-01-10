pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sccript{
                    sh'mvn clean package'
                }
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
    }
}
