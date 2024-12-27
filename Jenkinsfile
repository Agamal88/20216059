pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                // Clones the repository
                git url: 'https://github.com/Agamal88/20216059.git', branch: 'main'
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
