pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'Echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
