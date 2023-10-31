pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                checkout scmGit(branches: [[name: '*/develop']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/ajit2525/Bitwise-Workshop.git']])
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello World Good Morining!!'
            }
        }
    }
}
