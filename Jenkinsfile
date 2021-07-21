pipeline
{
    agent any
    stages
    {
        stage('ContinuousDownload-Master')
        {
            steps
            {
                git 'https://github.com/krishnain/mavennew.git'
            }
        }
        stage('ContinuousBuild-Master')
        {
            steps
            {
                sh 'mvn package'
            }
        }
    }
    
    
    
    
    
    
}
