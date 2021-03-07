properties([pipelineTriggers([pollSCM('* * * * *')])])


pipeline{
    agent any
    tools{
        jdk 'jdk'
    }
    stages{
        stage('run'){
            steps{
                sh 'javac file1.java'
                sh 'java file1'
            }
        }
    }
}
