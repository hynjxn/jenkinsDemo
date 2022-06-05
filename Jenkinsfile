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
                echo '202206071100'
            }
        }
        
    }
    post {
        always{
            echo 'jenkins done ~'
        }
    }
}
