pipeline {
    agent any

    stages {
        stage('Declarative: Checkout SCM') {
            steps {
                checkout scm
            }
        }
        
        stage('Clone Repository') {
            steps {
                git 'https://github.com/Agamal88/20216059.git'
            }
        }

        stage('Execute Script') {
            steps {
                // Use the converted batch script
                bat 'list_files.bat'
            }
        }
    }
}
