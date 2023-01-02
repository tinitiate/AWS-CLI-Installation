# AWS-CLI-Installation

## Install Aws CLI

- Download and run the AWSCLI MSI installer for Windows (64-bit):
  For the latest version of the AWS CLI: AwsCLI
- Alternatively, you can run the msiexec command to run the MSI installer:
  
  `msiexec.exe /i <https://awscli.amazonaws.com/AWSCLIV2.msi>`

## Verify the CLI installation

- Run the following command to verify that the CLI installed successfully.
  
  `aws --version`
- If the installation was successful, the following message is returned
  
  `aws-cli/2.1.29 Python/3.7.4 Windows/10 botocore/2.0.0`

## Configure Aws CLI

- Run the following command to configure CLI
```
      aws configure -- profile "Name of the profile"
      
      AWS Access Key ID [None]: enter your access key
      
      AWS Secret Access Key [None]: enter your secret access key
      
      Default region name [None]: us-east-2
      
      Default output format [None]: json
```

