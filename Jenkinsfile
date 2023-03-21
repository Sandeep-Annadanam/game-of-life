node ('MAVEN'){
    stage("SCM"){
        git branch: 'main', url: 'https://github.com/spring-projects/spring-petclinic.git'
    }
    stage('CLEAN PACKAGE'){
        sh 'mvn clean'
    }
    stage('BUILD'){
        sh 'mvn package'
    }
}
