# aws-resource-automation
# AWS Resource Automation Script

## Overview
This shell script simplifies the process of managing AWS resources by listing resources across multiple services. It automates cloud management tasks and provides daily updates when run on an AWS EC2 instance.

## Features
- Supports 14+ AWS services, including EC2, S3, RDS, Lambda, and more.
- Validates AWS CLI setup and handles errors gracefully.
- Supports region-specific resource listing with tabular output.
- Flexible for customization and scaling.

## Usage
1. **Run Manually**:
   ```bash
   ./aws_resource_list.sh <aws_region> <aws_service>
