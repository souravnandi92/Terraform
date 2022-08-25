pipeline {
    agent any

    stages {
        stage('Connect with my Github Account - GitSCM') {
            steps {
                echo 'Hello World'
                git credentialsId: 'githubid', url: 'https://github.com/souravnandi92/Terraform.git'
            }
        }
    }
}
