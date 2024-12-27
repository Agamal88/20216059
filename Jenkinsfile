pipeline {
    agent any
    
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/Agamal88/20216059.git'
            }
        }
        stage('Execute Script') {
            steps {
                bat 'list_files.bat'  // assuming your script is now a .bat file
            }
        }
    }
}
