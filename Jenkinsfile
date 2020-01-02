pipeline {
    agent any
    
    environment {
        _version=createVersion()
    }
    
    stages {
        stage('Build') {
            steps {
                echo "${_version}"
            }
        }
    }
}
def createVersion() {
    return new Date().format('yyyyMM') + "-${env.BUILD_NUMBER}"
}
