 def dir = script('ls')
pipeline {
   
    agent any
    stages {
        stage('build') {
            steps {
                echo 'build step'
            }
        }
        stage('qa') {
            steps {
                echo 'qa step'
            }
        }
        stage('qa2') {
            steps {
                echo 'qa2 step'
            }
        }
        stage('powershell') {
            steps {
               
               println dir
            }
        }
    }
}
