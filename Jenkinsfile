pipeline {
    agent {
        node {
            label 'Jenkins-Slave-KR'
        }
    }

    stages {
        stage('Build and package') {
            steps {
                echo "Building and installing spring utils"
                sh "mvn clean install"
            }
        }
    }
}
