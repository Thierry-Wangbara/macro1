pipeline {
    agent any
    
    stages {
        stage('Construction') {
            steps {
                echo 'Construction du projet en cours...'
                sh 'echo "Build OK"'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Lancement des tests...'
                sh 'echo "Tests OK"'
            }
        }
    }
    
    post {
        success {
            echo 'Le pipeline a réussi avec succès !'
        }
        failure {
            echo 'Le pipeline a échoué.'
        }
    }
}

