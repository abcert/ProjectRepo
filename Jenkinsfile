#!groovy

library(
  identifier: 'jenkins-shared-library@master',
  retriever: modernSCM(
    [
      $class: 'GitSCMSource',
      remote: 'https://github.com/abcert/jenkins-shared-library.git'
    ]
  )
)

/*
cdoPipeline {
  developmentRepositoryBranch = 'master'
  stagingRepositoryBranch = 'release'
  productionRepositoryBranch = 'master'
  slackNotificationChannel = '#backend-events'
  swaggerYamlFilename = 'newservice.yaml'
  projectName = 'newservice'
}
*/

buildPipeline{
  crNumber = "CR12345"
  ticketNumber = "T3403940234"
  deploymentDate = "10/14/2019"
  javaModule="javamodule"
  scalaModule="scalamodule"
  testTeamDLOrPersonEmailID="certification82@gmail.com"
  devTeamDLOrPersonEmailID="certification82@gmail.com"
  opsTeamDLOrPersonEmailID="certification82@gmail.com"
}
