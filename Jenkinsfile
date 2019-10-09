#!groovy

@Library('jenkins-shared-library') _

backendServicePipeline {
  developmentRepositoryUrl = 'git@heroku.com:dev-newservice-repository.git'
  stagingRepositoryUrl = 'git@heroku.com:stg-newservice-repository.git'
  productionRepositoryUrl = 'git@heroku.newservice-repository.git'
  slackNotificationChannel = '#backend-events'
  swaggerYamlFilename = 'newservice.yaml'
  projectName = 'newservice'
}
