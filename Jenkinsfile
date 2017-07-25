node {
    stage('checkout') {
        checkout scm
    }    

    stage('build') {
        withMaven( jdk: 'JDK 8', maven: 'MVN 3'){
            sh "mvn clean install"
        }
    }
}
