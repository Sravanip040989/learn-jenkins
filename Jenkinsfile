pipeline {
    agent {
        label 'AGENT-1'
    }
    options {
        timeout(time: 1, unit: 'HOURS')
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo This is Build'
            }
        }
        stage('Test') {
            steps {
                sh 'echo This is Test'
                sh 'sleep 10'
	    }
        }
        stage('Deploy') {
            steps {
                sh 'echo This is Deploy'
            }
        }
    }
}