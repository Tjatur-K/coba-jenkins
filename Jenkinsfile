pipeline {
    agent { any { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'echo 'Selamat datang di Jenkins Pipeline''
                sh 'javac *.java'
                sh 'java TestMobil'
            }
        }
    }
}
