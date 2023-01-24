node {
    stage('Checkout SCM') {
        git branch: 'master', url: 'git@github.com:vivekpatil8/MEANCRUD_client.git'
    }

    stage('Install node modules') {
        sh "npm install"
    }
}
