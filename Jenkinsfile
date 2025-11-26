pipeline {
    agent any

    stages {
        stage('update and install mvn') {
            steps {
                sh "sudo apt update"
              sh  "sudo apt install maven -y"
            }
        }
      
        stage('checkout') {
            steps {
                sh "rm -rf hello-world-war"
              sh  "git clone https://github.com/vinayak432/hello-world-war/"
            }
        }
      
    }
}
