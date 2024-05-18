pipeline {
    agent any

    stages {
        stage('Checkout Repo 1') {
            steps {
                git url: 'https://github.com/kholoudKamkhli/Jenkins'
            }
        }
        stage('Execute Script from Repo 1') {
            steps {
                bat 'batch_file.bat'  // Assuming this script is a batch file to be executed on a Windows agent
            }
        }
        stage('Checkout Repo 2') {
            steps {
                git url: 'https://github.com/esraakhalifa/List-Files-Bash-Script'
            }
        }
        stage('Execute Script from Repo 2') {
            steps {
                bat 'list_files.bat'  
            }
        }
    }
}
