pipeline{
    agent any
    stages{
        stage('checkout'){
            step{
                git credentialsId: 'git', url: 'https://github.com/vijaytejapatel/first-project.git'
            }
        }
    }
}
