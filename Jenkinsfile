pipline{
    agent any
    stages {
        stage("test"){
            steps{
                echo "Testing the project"
            }
        }
        stage("Build"){
            steps{
                docker build -t myimage .
            }
        }
        stage("deploy"){
            steps{
                echo "deploying"
            }
        }
    }
}