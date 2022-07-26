pipeline {
    agent any

    stages {
        stage('clone project') {
            steps {
                echo 'Cloning project....'
                git changelog: false, credentialsId: 'git-user', poll: false, url: 'https://github.com/Suren3010/Sample.Project.git'
                git changelog: false, poll: false, url: 'https://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@github.com/Suren3010/Sample.Project.git'
                echo 'Project cloned...'
            }
        }
    }
}