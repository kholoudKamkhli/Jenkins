pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/kholoudKamkhli/Jenkins'  // Replace with your repository URL
            }
        }
        stage('Execute Bash Script') {
            steps {
                bat 'batch_file.bat'  // Replace with the path to your bash script
            }
        }
    }
}
