node {
 
    stage('Checkout') {
        checkout scm
    }
 
    stage('Clean') {
        sh 'mvn clean'
    }
 
    stage('Validate') {
        sh 'mvn validate'
    }
 
    stage('Compile') {
        sh 'mvn compile'
    }
 
    stage('Test') {
        sh 'mvn test'
    }
 
    stage('Package') {
        sh 'mvn package'
    }
 
    stage('Verify') {
        sh 'mvn verify'
    }
 
    stage('Install') {
        sh 'mvn install'
    }
 
    stage('Site') {
        sh 'mvn site'
    }
 
    stage('Deploy') {
        sh 'mvn deploy'
    }
}
