@Library('global-shared-library@master')
pipeline {
    agent any
    
    environment {
        _version=createVersion()
    }
    
    stages {
        stage('Build') {
            steps {
                script{
                    def util=new com.mafeifan.Utils()
                    def version=util.createVersion("${BUILD_NUMBER}")
                    echo "${version}"
                    sayHello 'yes'
                    echo "${_version}"
                }
            }
        }
    }
}
def createVersion() {
    return new Date().format('yyyyMM') + "-${env.BUILD_NUMBER}"
}
