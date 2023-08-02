pipeline {
    agent any

    stages {
        stage("build") {
          steps {
                echo 'building my application...'
            }
        }

        stage("test") {
            steps {
                git'https://github.com/Bussyoshodi7/Jenkinsfile-project.git'
            }
        }
        stage("deploy") {
           steps {
              echo 'deploying my application...'
            }
        }
    }
}
