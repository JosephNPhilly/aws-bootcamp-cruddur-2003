# Week 0 — Billing and Architecture
- update gipod.yml file: following this link [link install aws cli linux](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

  tasks: 
  - name: aws-cli
    env: 
    AWS_CLI_AUTO_PROMT: on-partial
    init: |
  cd /workplace
  curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
  unzip awscliv2.zip
  sudo ./aws/install
  cd $THEIA_WORKPLACE_ROOT
