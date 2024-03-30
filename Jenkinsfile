pipeline{
    agent any
    triggers{
        githubPush()
    }
    stages{
        stage("test"){
            steps{
                bat 'npm -v'
                echo "done..."
            }
        }
    }
}