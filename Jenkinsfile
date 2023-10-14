pipeline
{
  agent any
  stages
  {
    stage ('Build')
    {
      steps
      {
        echo 'this pipeline build by SOHAM'
      }

       stage ('Test')
    {
      steps
      {
        echo 'this pipeline test by BHAVESH'
      }

       stage ('Deploy')
    {
      steps
      {
        echo 'this pipeline deploy by PANDEY'
      }
    }
  }  

  post
      {
        always
        {
          emailtext body: 'Summary' , subject: 'Pipeline Status' , to: 'sdpatil764@gmail.com'
        }
      }
    }  
