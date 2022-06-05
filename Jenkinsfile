pipeline {
    agent {
        label "demoAgent"
    }
    parameters {
        string(name: 'TIME', defaultValue: 'Hello Hongik~', description: 'What should I say?')
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        
        stage('Time') {
            steps {
                sh('echo ${TIME}')
            }
        }
        
    }
    post {
        always{
            echo 'jenkins done ~'
        }
    }
}
