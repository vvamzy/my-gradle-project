pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                git 'https://github.com/vvamzy/my-gradle-project.git'
            }
        }
         stage('Building with gradle') {
            steps {
                sh 'gradle clean build'
            }
        }
    }
}
