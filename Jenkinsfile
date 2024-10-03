node("linux") {
    stage('Checkout') { // for display purposes
       checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/francy2019/cloudCampJenkins.git']])
    }
    stage('Checkfiles') {
        sh 'ls -la'
    }
    stage('Setup Java') {
        java -version
    }
}
