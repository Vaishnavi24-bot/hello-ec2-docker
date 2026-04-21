stage('Run Container') {
    steps {
        sh '''
        docker stop devops-web-app || true
        docker rm devops-web-app || true
        docker run -d --name devops-web-app -p 8080:8080 devops-web-app
        '''
    }
}
