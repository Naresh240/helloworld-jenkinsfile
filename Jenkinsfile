pipeline{
    agent any
    
    stages {
        stage("Running_Shell_Script") {
            steps {
                sh '''
                    chmod +x ./example.sh
                    ./example.sh
                '''
            }
        }
    }
}