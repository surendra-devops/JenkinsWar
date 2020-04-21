pipeline {
    agent any

    def color = params.color
    def size = params.size

    stages {
        stage('build') {
            steps {
                echo "Build"
            }
        }
        stage('deploy') {
            steps {
                echo "Deploy"
            }
        }
        stage('build-test') {
            steps {
                echo "test"
            }
        }
    }
}
