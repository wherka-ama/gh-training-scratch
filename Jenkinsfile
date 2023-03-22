pipeline {
    agent any
    stages {
        stage('Listing') {
            steps {
                sh 'ls -ltrha'
            }
        }
    }
    post { 
        always { 
            echo "I'm doooone"
        }
    }
}
