pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                echo $build.number
            }
        }
    }
}
