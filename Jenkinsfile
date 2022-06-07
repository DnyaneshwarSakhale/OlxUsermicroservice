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
    }
}
