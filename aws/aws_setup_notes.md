### AWS Setup Documentation

#### Install (brew) packages: terraform, awscli

#### Provision AWS IAM user

1) Create new IAM user

2) Create new group

3) Add user to group

4) Securely store credentials

#### Enable MFA

1) Enable MFA and store recovery key securely

#### Setup Password Policy

1) Setup password policy

#### Configure CLI [see https://blog.gruntwork.io/authenticating-to-aws-with-the-credentials-file-d16c0fbcbf9e for helpful tips]

1) run 'aws configure'
    => stores credentials    in "$HOME/.aws/credentials"
    => stores other settings in "$HOME/.aws/config"

### TERRAFORM SIDE

[from https://www.terraform.io/docs/providers/aws/index.html]
"You can use an AWS credentials file to specify your credentials. The default location is $HOME/.aws/credentials on Linux and OS X"

[Already configured in above 'Configure CLI' step]


#### HOW TO FIND AN AMI

see https://www.andreagrandi.it/2017/08/25/getting-latest-ubuntu-ami-with-terraform/

example for 18.04 encrypted => https://gist.github.com/AlainODea/be4fd6fc53bfbbcad45a7a9989db6c4e







