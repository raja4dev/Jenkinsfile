pipeline{

    agent any
   

    environment
    {
    ARTIFACTORY_CREDS = credentials ('20ba63a3-225e-4dd1-98ae-7894ac44717e')
    }
stages{
    stage('build')
        {
      steps{
          script{
              echo "${ARTIFACTORY_CREDS}"
}

}
 }
}
}
