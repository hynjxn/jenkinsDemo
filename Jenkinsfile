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
                echo "${TIME}"
            }
        }
        
    }
    post {
        always{
            echo 'jenkins done ~!!!!'
        }
    }
}
