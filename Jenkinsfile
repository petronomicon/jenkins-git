pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hellraiser 23: Breadraiser"'
                sh '''
                    echo "Multiline shell steps works too good to be ture"
                    ls -lah
                '''
            }
        }
    }
}
