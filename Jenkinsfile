pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build App'
            }
        }
        stage('Test') {
            steps {
                echo 'Test App'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy App'
            }
        }
        
        stage('Declarative Post Actions') {
            steps {
                echo 'Declarative App'
            }
        }
    }
    
    post {
        failure {
            mail bcc: '', body: 'When you are trying to run the build', cc: '', from: '', replyTo: '', subject: 'Jenkin Stage Failure', to: 'rudrag.scm@gmail.com'
        }
    }
}
