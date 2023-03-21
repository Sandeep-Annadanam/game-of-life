node {
    stage("SCM"){
        git 'https://github.com/Sandeep-Annadanam/game-of-life.git'
    }
    stage('CLEAN PACKAGE'){
        sh 'mvn clean'
    }
    stage('BUILD'){
        sh 'mvn package'
    }
}
