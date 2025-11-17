pipeline {
    agent any

    stages {

        stage('clear working directory') {
            steps {
               sh 'rm -r *'
                sh 'rm -r ../../../../www/html/*'
            }
        }

        stage('clonning from scm') {
            steps {
               sh 'git clone https://github.com/syash4069-png/Jenkins.git'
            }
        }

        stage('copy to html') {
            steps {
                sh 'mv'
            }
        }

    }
}
