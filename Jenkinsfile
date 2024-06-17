pipeline {
    agent any

    stages {
        stage('Build') {
            when {
                branch 'main'
            }
            steps {
                echo 'Building on main branch...'
            }
        }
        stage('Test') {
            when {
                branch 'feature/*'
            }
            steps {
                echo 'Testing on feature branch...'
            }
        }
    }
}
