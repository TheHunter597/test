pipline{
    agent any
    stages {
        stage("test"){
            steps{
                script{
                    echo "testing"
                }
            }
        }
        stage("Build"){
            steps{
                script{
                   sh "docker build -t myimage ."
                }
            }
        }
        stage("deploy"){
            steps{
                script{
                    echo "deploying"
                }
            }
        }
    }
}