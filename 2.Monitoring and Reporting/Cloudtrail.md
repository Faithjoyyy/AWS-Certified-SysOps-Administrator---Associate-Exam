## AWS CloudTrail Overview

AWS CloudTrail is a service that enables governance, compliance, and operational auditing of your AWS account. It records account activity and API usage across AWS services, providing a detailed history of actions taken through the AWS Management Console, SDKs, CLI, and other AWS services.

###  Key Features

- **Tracks API Calls**: CloudTrail logs every API call made in your AWS account, including:
  - Who made the request
  - When it was made
  - What actions were performed
  - Which resources were affected

- **User Activity Monitoring**: Helps identify unauthorized access or unusual behavior by tracking user actions and access patterns.

- **Event History**: Provides a searchable history of events for the past 90 days by default, useful for troubleshooting and security analysis.

- **Integration with CloudWatch**: CloudTrail events can be sent to CloudWatch Logs for real-time monitoring and alerting.

- **Data Events**: Tracks operations on data resources like S3 objects and Lambda functions, offering deeper visibility into data-level access.

- **Multi-Region & Organization Support**: Automatically logs events across all AWS regions and supports centralized logging for AWS Organizations.



CloudTrail is essential for maintaining visibility, accountability, and security in AWS environments. It complements CloudWatch by focusing on who did what and when, making it a critical tool for audit trails and forensic investigations.
