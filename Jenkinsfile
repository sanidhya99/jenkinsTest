pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                // Clean workspace before cloning (optional)
                deleteDir()

                // Clone the Git repository
                git branch: 'master', url: 'https://github.com/adrianhajdin/chat_application.git'
            }
        }

        // Additional stages and steps can be added here
    }
}
