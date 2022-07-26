pipeline {
    agent any

    stages {
        stage('clone project') {
            steps {
                echo 'Cloning project....'
                git changelog: false, poll: false, url: 'https://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@github.com/Suren3010/Sample.Project.git'
                echo 'Project cloned...'
            }
        }
    }
}