pipeline {
    agent any 
    triggers{
        issueCommentTrigger('.*')
    }
    stages{
        stage("test") {
            steps {
                echo '${env.GITHUB_COMMENT}'
                
            }
        }
    }
}