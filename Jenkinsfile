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

cdoPipeline {
  developmentRepositoryBranch = 'master'
  stagingRepositoryBranch = 'release'
  productionRepositoryBranch = 'master'
  slackNotificationChannel = '#backend-events'
  swaggerYamlFilename = 'newservice.yaml'
  projectName = 'newservice'
}
