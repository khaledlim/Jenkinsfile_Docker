pipeline {
    agent {
        docker {
            image 'hello-world'
        }
    }
    stages {
        stage('Build') {
            steps {
                echo "JenkinsFile + Docker"
                cmd_exec('docker -v')
            }
        }
    }
}
