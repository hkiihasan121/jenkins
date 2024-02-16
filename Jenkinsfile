pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('world') {
            steps {
                echo 'this is pipeline'
            }
        }
        stage('enviroment') {
            steps {
                echo env.BUILD_ID
                echo env.JENKINS_HOME
                echo env.JOB_NAME
            }
        }
    }
}

