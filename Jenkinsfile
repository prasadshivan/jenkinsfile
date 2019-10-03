pipeline {
    agent none 
    stages {
        stage('Example Build') {
            agent any 
            steps {
                echo 'Hello, world'
            }
        }
        stage('Example Test') {
            agent any
            steps {
                echo 'Hello, JDK'
            }
        }
    }
}
