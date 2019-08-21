node {
    powershell 'Write-Output "Hello, World!"'
    docker.image('node:7-alpine').inside {
        stage('Test') {
            sh 'node --version'
        }
    }
}
}
