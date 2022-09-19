pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World" > /tmp/root'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
