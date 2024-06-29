pipeline{
    DOCKERHUB_CREDENTIALS=credentials("dockerDevopsId")
                           
    agent any
    stages{
        stage('recuperation code depuis github'){
            steps {
                echo 'code pulled Ok'
            }
        }



        stage('going to the construction image docker '){
            steps{
                echo 'coming soon'
            }
        }
        stage('Build Docker Image'){
            steps{
                sh 'build docker devopsDocker .'
            }
        }



    }
}