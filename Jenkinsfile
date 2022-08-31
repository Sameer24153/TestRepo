pipeline
{
    agent any
    
    environment
    {
        USER_NAME = "SAM"
        USER_AGE = 22
    }
    
    stages
    {
        stage('Env Vars')
        {
            steps
            {
                echo "BUILD_NUMBER = ${env.BUILD_NUMBER}"
                echo "$USER_NAME"
                echo "$USER_AGE"
                echo "$USER_LOC"
            }
        }
    }
}
