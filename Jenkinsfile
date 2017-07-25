node {
    stage('checkout') {
        git 'https://github.com/comquent/MultiBranchSample.git'
    }    

    stage('build') {
        withMaven( jdk: 'JDK 8', maven: 'MVN 3'){
            sh "mvn clean install"
        }
    }
}
