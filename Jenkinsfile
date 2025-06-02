pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/studydny182/jenkins-demo-app.git'
            }
        }
        stage('Deploy') {
            steps {
                sh 'cp index.html /var/www/html/index.html'
            }
        }
    }
}
