pipeline{
    agent any
    triggers{
        githubPush()
    }
    stages{
        stage("test"){
            steps{
                sh 'npm -v'
                echo "done..."
            }
        }
    }
}