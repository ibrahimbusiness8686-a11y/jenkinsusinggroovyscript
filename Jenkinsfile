pipeline{
    agent any
    stages{
       stage('build'){
        steps{
        bat 'javac ibbu.java'
       }
       }

       stage('test'){
        steps{
        bat 'java ibbu'
       }
       }
       stage('deploy'){
        steps{
        echo 'deployment successful'
        }
    }
}
}
