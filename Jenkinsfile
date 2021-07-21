pipeline
{
    agent any
    stages
    {
        stage('ContinuousDownload-Master')
        {
            steps
            {
                git 'https://github.com/intelliqittrainings/maven.git'
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
