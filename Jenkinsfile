pipeline{
    agent any
    tools{
        maven 'Maven'
    }
    stages{
        stage('checkout sql source projects') {
            steps {
                git url: 'https://github.com/uteegozi/Jenkinsfile-test-data.git'
            }
        }
        stage('build assembly project') {
            steps {
                script {
                    sh 'mvn clean install'
                }
            }
        }
    }
}