properties([pipelineTriggers([githubPush()])])
pipeline{
    agent any
    tools{
        jdk 'jdk'
    }
    stages{
        stage('run'){
            steps{
                sh 'javac hello.java'
                sh 'java hello'
            }
        }
    }
}
