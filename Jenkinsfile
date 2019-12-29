pipeline {
    def msg = powershell(returnStdout: true, script: 'Write-Output "PowerShell is mighty!"')
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
               
               println msg
            }
        }
    }
}
