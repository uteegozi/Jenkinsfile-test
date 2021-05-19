pipeline{
    agent any
    stages{
        stage('checkout sql source projects') {
            steps {
                git url: 'https://github.com/uteegozi/Jenkinsfile-test-data.git'
            }
        }
//         stage('build assembly project') {
//             steps {
//                 script {
//                     new MavenCommand(this, ['-fae'])
//                     .inDirectory('Jenkinsfile-test')
//                     .run('clean install')
//                 }
//             }
//         }
    }
}