# AWS-Connect CLI

AWS-Connect is a Command Line Interface (CLI) tool built using Python and Typer to manage AWS services efficiently from the terminal. It allows users to log in, manage EC2 instances, S3 buckets, and view billing information.

## Features
- Login using an existing AWS profile or add a new account
- Manage EC2 instances (start, stop, list, etc.)
- Perform S3 operations (upload, download, list, etc.)
- View AWS billing & cost management information

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.10+
- AWS CLI (configured with credentials)
- Pip

### Install the CLI
You can install `aws-connect-cli` from PyPi:
```sh
pip install aws-connect-cli
```

## Usage
Once installed, you can run the CLI using:
```sh
aws
```

### Available Commands
```sh
aws login    # Choose an AWS profile or add a new account
aws billing  # View AWS billing & cost management info
aws ec2      # Manage EC2 instances
aws s3       # Perform S3 operations
```## Example Usage
### Login to AWS
```sh
aws login
```
### List EC2 Instances
```sh
aws ec2 list
```
### Upload a File to S3
```sh
aws s3 upload myfile.txt my-bucket
```

## Development
### Clone the Repository
```sh
git clone https://github.com/AutoDictate/aws-connect-cli.git
cd aws-connnect-cli
```
### Install Dependencies
```sh
pip install -r requirements.txt
```
### Run the CLI Locally
```sh
python aws_connect-cli.py
```

## Contributing
Feel free to open issues and submit pull requests.

## License
This project is licensed under the MIT License.

