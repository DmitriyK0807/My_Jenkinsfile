pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                git credentialsId: 'ssh_key_for_web_server', url: 'https://github.com/DmitriyK0807/Repo_For_Jenkins_Pipeline'
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
