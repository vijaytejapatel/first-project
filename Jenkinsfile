pipeline{
    agent any
    stages{
        stage("checkout"){
            steps{
                git credentialsId: 'git', url: 'https://github.com/vijaytejapatel/first-project.git'
            }
        }
    }
}
