pipeline {
    agent any

    stages {
        stage('clone project') {
            steps {
                echo 'Cloning project....'
                git changelog: false, poll: false, url: 'https://github.com/Suren3010/Sample.Project.git'
                echo 'Project cloned...'
            }
        }

        stage('build solution') {
            steps {
                dotnetRestore project: 'Sample.Project.sln', sdk: 'dotnet-sdk'
            }
        }
    }
}