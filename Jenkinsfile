pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Git Branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
        stage('docker build') {
            steps {
                sh('pwsh -version')
                //pwsh(script: 'docker image -a')
            }
        }
    }
}
