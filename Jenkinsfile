pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stage('git clone') {
            steps {
                git 'mvm '
            }
        }
        stage('compile') {
            steps {
                echo 'mvm complie'
            }
        }
        stage('test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
