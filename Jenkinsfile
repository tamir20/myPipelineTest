pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/tamir20/myPipelineTest.git'
                bat 'mvn clean package'
            }
        }
    }
}
