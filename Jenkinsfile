pipeline {
    agent {
        docker {
            image 'frekele/ant' 
            args '' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh '/usr/bin/ant' 
            }
        }
    }
}
