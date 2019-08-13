pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
                sh '''
                    echo "bla bla new list
                '''
                sh '''
                    ls
                '''
            }
        }
    }
}
