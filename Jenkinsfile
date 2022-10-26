pipeline{
    agent any
    stages{
         stage('Vm Create'){
            steps{
                sh 'chmod 777 bin.sh'
                sh '/var/lib/jenkins/workspace/Azcli/bin.sh'

            }
        }
    }
}