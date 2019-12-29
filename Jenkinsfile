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
               def dirList = powershell(returnStdout: true, script: 'dir')
               echo $dirList
            }
        }
    }
}
