pipeline{
    agent any
    stages{
        stage('VCS'){
            steps{
                git branch : 'main' , url: 'https://github.com/mallojuashok/MyPractice.git'
            }

        }
        stage('Vm Create'){
            steps{
                sh 'chmod +x bin.sh'
                sh 'bin.sh'

            }
        }
    }
}