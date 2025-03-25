pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', credentialsId: 'github-credentials', url: 'https://github.com/JPRocha14/git-jenkins-integracao.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Construindo o projeto...'
            }
        }

        stage('Test') {
            steps {
                echo 'Executando testes...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Fazendo o deploy...'
            }
        }
    }
}
