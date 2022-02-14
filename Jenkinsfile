pipeline {
    agent {
    dockerfile {
        filename 'Dockerfile'
        registryUrl 'https://hub.docker.com/repository/docker/dmitriyk0807/my_web_page'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                git credentialsId: 'ssh_key_for_web_server', url: 'https://github.com/DmitriyK0807/Repo_For_Jenkins_Pipeline'
            }
        }
    }
}
