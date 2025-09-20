pipeline {
    agent {
  label 'dev'
}
tools {
  maven 'maven'
}
    stages {
        stage('Git') {
            steps {
                git 'https://github.com/PranithaGoud8/dicet_tv.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
            }
    }
}
