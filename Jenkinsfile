pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/amolgautam1221/nginx-web-app.git'
            }
        }
        stage('Build') {
            steps {
                echo "Build successful"
            }
        }
        stage('Deploy') {
            steps {
                sh 'cp -r * /usr/share/nginx/html/'
            }
        }
    }
}
                            
