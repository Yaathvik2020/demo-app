// The whole pipeline lives in the shared library (repo: jenkins-shared-library).
// App teams only say WHAT they want; the DevOps team owns HOW it is built and deployed.
@Library('company-pipeline') _

javaPipeline(
  appName : 'demo-app',
  devPort : 8081,
  qaPort  : 8083,
  prodPort: 8082
)
