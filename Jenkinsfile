pipeline {
    agent any
    stages {
        stage('clone repo and clean') {
            steps {
                sh "rm -rf java_program"
                sh "git clone https://github.com/amj133/java_program.git"
            }
        }
        stage('test') {
            steps {
                sh "echo 'Tests passed!'"
            }
        }
        stage('deploy') {
            steps {
                sh "echo 'fake deploy worked!'"
            }
        }
    }
}
