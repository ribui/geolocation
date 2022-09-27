pipeline {
    agent any
    triggers {
  pollSCM '* * * * *'
}

    stages {
        stage('code checkout') {
            steps {
                echo 'Hello World'
                sleep 5
            }
        }
        stage('Build') {
            steps {
                echo 'Hello Build'
                sleep 5
            }
        }
        stage('Test') {
            steps {
                echo 'Hello Test'
                sleep 5
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello Deploy'
                sleep 5
            }
        }
    }
}