pipeline {
    agent {label 'linux'}
    stages {
        stage ('checkout') {
            steps {
                echo "This is checkout stage"
            }
        }
        parameters {
            choice choices:{ 'Prod','UAT','Dev' },name: ''environment 
        stage ('build') {
            steps {
                echo "This is build stage"
            }
        }
        stage ('sonarscan') {
            steps {
                echo "This is sonarscan stage"
            }
        }               
        stage ('push') {
            steps {
                echo "This is push stage"
            }
        }
        stage ('deploy') {
            steps {
                echo "This is deploy stage"
            }
        }                    
    }
}
