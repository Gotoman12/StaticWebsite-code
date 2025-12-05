pipeline{
    agent any
    stages{
        stage("GIT-CHECKOUT"){
            steps{
                git url:'https://github.com/Gotoman12/StaticWebsite-code.git',branch:'staging'
            }

        }
        stage("Hello-World"){
            steps{
                echo "Pipeline is completed"
            }

        }
    }
}