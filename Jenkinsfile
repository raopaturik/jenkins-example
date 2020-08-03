pipeline {
    agent none
    
        tools {
        // The M3 maven tool must be already configured in
        // Manage Jenkins -> Global Tool Configuration -> Maven
        maven 'M3'
    }

    stages {

        stage ('Build') {
            agent any

            steps {
                echo 'Build Completed'
              
            }
        }

        stage ('Deploy') {
            agent any

            steps {
                echo 'Deploy Completed'
            }
        }

        stage ('Test') {
            agent any

            steps {
                echo 'Test Completed'
            }
        }

        stage ('Release') {
            agent any

            steps {
                echo 'Release Completed'
            }
        }

    }
}
