pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Beulah124/MyWebsiteRepo.git'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the HTML file...'
                // This is where you'd deploy your HTML file, e.g., copy to a web server
            }
        }
    }
}
