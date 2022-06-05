pipeline {
    agent {
        label "demoAgent"
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        
        stage('Time') {
            steps {
                echo 'time'
            }
        }
        
    }
    post {
        always{
            echo 'jenkins done ~'
        }
    }
}
