# CICD_security_testing
A GitLab pipeline that will build, and test a vulnerable webserver, and a hardened webserver. Tests will be conducted with Zap Proxy and SonarQube in the Pipeline, prior to deployment.

## To Do
- [ ] [Purchase a domain name](https://www.domain.com/domains) for this project
  - [ ] * [Google Cloud CLI install Instructions](https://cloud.google.com/sdk/docs/downloads-interactive)
- [ ] Run [GitLab](https://docs.gitlab.com/ee/install/google_cloud_platform/) either in GKE or GCP hosted VM
- [ ] Set up Pipeline that builds two web applicaitons:
  - [ ] One vulnerable [One or more of the apps listed here](https://geekflare.com/practice-hacking-legally/)
  - [ ] One home made (possible create-react-app with small modificaiton)
- [ ] Test the Source code in a staging environment using [SonarQube](https://docs.sonarqube.org/9.6/try-out-sonarqube/)
- [ ] Test the built application in a staging environment using [Zap Proxy](https://www.zaproxy.org/docs/automate/ )
- [ ] Push a secure Web App to production


## Nice to have follow on features:
- [ ] [Free Duo MFA authentication]([https://signup.duo.com/](https://duo.com/editions-and-pricing/duo-free)) applied to Gitlab and Google Cloud logins
