properties([pipelineTriggers([githubPush()])])
node('linux') {
    git url: 'https://github.com/jonyeneho/infrastructure-pipeline.git', branch: 'master'
    stage('Test') {
        sh "env"
    }
}
