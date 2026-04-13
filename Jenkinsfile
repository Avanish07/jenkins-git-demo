pipeline {
    agent any

    stages {
        stage('Clone & Run') {
            steps {
                sh 'chmod +x app.sh'
                sh './app.sh'
            }
        }
    }
}
