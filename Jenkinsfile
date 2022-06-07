pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                 bat 'mvn clean compile'
            }
            }
        stage('Run') {
            steps {
                bat 'mvn package'
            }
            }
        stage('Test Report using jacoco') {
            steps {
            jacoco()
            }
            }
        stages('building docker image'){
            steps{
                echo 'building docker image'
            }
            }
            }
            }
