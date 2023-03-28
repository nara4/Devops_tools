pipeline {
    agent {label 'slave1'}
    stages {
        stage ('hello') {
            steps {
                sh '/home/ec2-user/Devops_tools/nsr.sh'
            }
        }
    }
}
