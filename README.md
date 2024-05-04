# AWS SAM
### SAM Setup
- Check if aws cli is already installed `aws --version`
- Check if sam cli is already installed `sam --version`
- Install aws cli: https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
- Install sam cli: https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/install-sam-cli.html
- Configure aws cli: https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html 


#### Build and Deploy
- Validate template: `sam validate -t <template file name>.yaml --lint`
- Build template: `sam build -t <template file name>.yaml`
- Deploy: `sam deploy --guided`

