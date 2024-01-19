## AWS Reminder App

Created using AWS

A serverless web application that allows users to schedule a reminder message to be sent to their Email. This application uses:
* Amazon SES for sending Email messages.
* Lambda for running Python functions serverlessly.
* IAM for managing permissions.
* Step Functions for creating a state machine that allows the app to schedule function calls.
* API Gateway for creating an API to call Lambda functions.
* S3 for hosting the application front end.

This repo contains the files used for Lambda functions, S3 bucket policy and state machine format, as well as the front end files.


![App](https://github.com/nvasiu/ReminderApp/assets/46430801/5b098ad1-8ad5-4171-8d99-c6a6147e08a9)
|:--:| 
| **Reminder App** |

![Email](https://github.com/nvasiu/ReminderApp/assets/46430801/97b04e05-941e-4289-b651-dbef03a70e21)
|:--:| 
| **Example Reminder Email** |

