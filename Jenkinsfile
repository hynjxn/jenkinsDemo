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
                echo "$(date)"
            }
        }
        
    }
    post {
        always{
            echo 'jenkins done ~'
        }
    }
}
