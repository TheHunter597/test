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
                    docker build -t myimage .
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