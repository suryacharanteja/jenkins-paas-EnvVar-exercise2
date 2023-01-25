pipeline {
    agent any
    environment { 
        CC = 'clang'
    }
    stages {
        stage('stage-EnvVar-all') {
            environment { 
                DEBUG_FLAGS = '-g'
            }
            steps {
                sh 'printenv'
            }
        }
    }
}
