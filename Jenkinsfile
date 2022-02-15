pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                git credentialsId: 'ssh_key_for_web_server', url: 'https://github.com/DmitriyK0807/Repo_For_Jenkins_Pipeline'
                sh 'docker build -t dmitriyk0807/my_web_page_2:v1'
                sh 'docker push dmitriyk0807/my_web_page_2:v1'
            }
        }
    }
}
