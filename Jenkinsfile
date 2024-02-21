pipeline{
    agent any
    tools {
      maven 'maven3'
        }

    stages{
        stage("Git Checkout"){
            steps{
                git 'https://github.com/snehamadhavi757/simple-app.git'
            }
        }
        stage("Build"){
            steps{
                sh script: "mvn clean package"
            }
        }

                
    }
}
