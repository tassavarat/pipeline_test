node('docker') {
    stage('Build') {
        docker.image('golang:1.17.5-alpine').inside {
            sh 'go version'
        }
    }
}
