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

        stage('Deploy') {
            steps {
                echo %date:-=% %time:-=%
            }
        }
    }
    post {
        always{
            echo 'jenkins 실습 done ~~'
        }
    }
}
