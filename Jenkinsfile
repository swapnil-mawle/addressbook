pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                echo "compile"
                sh "mvn build"
            }
        }
        stage('UnitTest') {
            steps {
                echo "Unit Test"
                sh "mvn test"
            }
        }
        stage('Package') {
            steps {
                echo "Package"
                sh "mvn package"
            }
        }
    }
}
