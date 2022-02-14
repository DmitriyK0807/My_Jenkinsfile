pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                git branch: '*/master', credentialsId: 'key_for_git', url: 'https://github.com/DmitriyK0807/Repo_For_Jenkins_Pipeline'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
