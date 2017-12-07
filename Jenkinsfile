pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh 'ls -al'
            }
        }
        stage('Test'){
            steps {
                sh 'echo "this is list"'
            }
        }
        stage('Deploy') {
            steps {
               build 'DemoOrg/Demo1/demo1Child1'
            }
        }
    }
}
