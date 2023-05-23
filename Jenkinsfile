pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'hello world'
                git branch: 'main', credentialsId: '785c9453-92b5-4be2-a7c7-abc9b4486016', url: 'https://github.com/yann-catlinn/thenew'
            }
        }
    }
}