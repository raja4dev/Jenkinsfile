pipeline{

    agent any
   
stages{
    stage('build')
        {
      steps{
          script{
            echo "Hello"
                }
            }
         }
       }
    
 post{
        always{
        echo "from always"
        }
        success{
        echo "from success"
        }
        failure{
        echo "Send eamil as its failed "
        }
    }
}
