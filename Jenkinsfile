pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git url: 'https://github.com/maxv33f1x5/jenkins-simple-demo.git',
                    branch: 'main'
            }
        }

        stage('Run script') {
            steps {
                sh 'chmod +x script.sh'
                sh './script.sh'
            }
        }
    }
}
