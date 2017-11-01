pipeline {
    agent {
        docker {
            image 'chaudhuri/ant' 
            args '-v /root/.m2:/root/.m2' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'ant' 
            }
        }
    }
}
