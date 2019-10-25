node('master')
{
  stage('ContinuousDownload') 
  {
    git 'https://github.com/rakeshguptha/multibranch.git'
  } 
  stage('ContinuousBuild')
  {
      sh label: '', script: 'mvn package'
  }
    
    
    
    
    
}
