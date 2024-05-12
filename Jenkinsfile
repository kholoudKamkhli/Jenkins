pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/kholoudKamkhli/Jenkins'  
            }
        }
        stage('Execute Bash Script') {
            steps {
                bat 'batch_file.bat'  
            }
        }
    }
}
