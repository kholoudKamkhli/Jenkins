pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/kholoudKamkhli/Jenkins'
                git url: 'https://github.com/esraakhalifa/List-Files-Bash-Script'
            }
        }
        stage('Execute Bash Script') {
            steps {
                bat 'batch_file.bat'  
            }
        }
    }
}
