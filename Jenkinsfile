pipeline{
    agent any 
    environment{
        name = "hareesh"
        wife = "srav"
    }
    stages{
        stage(env stage){
            steps{
            echo "current branch is ${env.BRANCH_NAME}"
        }
        }
        stage('environment stage'){
            environment{
                lover = "vyshu"
            }
            steps{
                echo "I am ${name}"
                echo "I am married to ${wife}"
                echo "I love ${lover}"
            }
        }
    }
}
