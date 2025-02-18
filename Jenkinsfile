pipeline {
    agent any
    stages {
        stage('compile') {
            steps {
                echo "compile"
                sh "mvn compile"
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
