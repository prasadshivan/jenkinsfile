pipeline {
    agent none 
    stages {
        stage('Example Build') {
            agent any 
            steps {
                echo 'Hello, Maven'
            }
        }
        stage('Example Test') {
            agent { Node1 'stage' } 
            steps {
                echo 'Hello, JDK'
            }
        }
    }
}
