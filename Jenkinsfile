pipeline {
    agent { Dockerfile true }
    stages {
        stage('Test') {
            steps {
                echo $build.number
            }
        }
    }
}
