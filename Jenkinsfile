pipeline {
    agent any
    stages {
        stage ('checkout scm'){
            echo 'pulling code from scm'
        }
        stage ('build'){
            echo 'mvn clean verify'
        }
    }
}