pipeline {
    agent any

    stages {
        stage('Checkout SCM') {
            steps {
                checkout([
                 $class: 'GitSCM',
                 branches: [[name: 'develop']],
                 userRemoteConfigs: [[
                    url: 'https://github.com/ajit2525/Demo1/tree/develop',
                    credentialsId: '',
                 ]]
                ])
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
