pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                git credentialsId: 'ssh_key_for_web_server', url: 'https://github.com/DmitriyK0807/Repo_For_Jenkins_Pipeline'
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
