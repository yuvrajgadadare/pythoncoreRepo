pipeline {
    agent any
    stages {
        stage("Version") {
            steps {
                bat "python --version"
            }
        }
        stage("Build") {
            steps {
                bat "Main.py"
            }
        }
    }
}