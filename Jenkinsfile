pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                // Clones the repository
                git url: 'https://github.com/your-username/your-repo-name.git', branch: 'main'
            }
        }
        stage('Execute Script') {
            steps {
                // Execute the bash script
                sh './list_files.sh'
            }
        }
    }
}
