pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build Phase!!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Phase!!'
            }
        }
        stage('Test') {
            steps {
                echo 'Test Phase!!'
            }
        }
    }
    post{
        always{
            emailext body: 'Dummy da', subject: 'Dummy', to: 'manohar.vijay001@gmail.com'
        
        }
    }
    
}
