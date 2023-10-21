pipeline{
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
                   sh "docker build -t thehunter597/test-mango:1.0.0 ."
                   sh "kubectl apply -f deployment.yaml"
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