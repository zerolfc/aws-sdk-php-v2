## aws-sdk-php-v2

PHP AWS SDK V2 Fork from aws/aws-sdk-php v2.8.31

### SNS

-   `PhoneNumber` for sending SMS
-   `setSMSAttributes` updates SMS attributes such as `MonthlySpendLimit`

### SQS

-   `createQueue` only work for **standard queue**
-   `MessageGroupId` required for FIFO (Your must create FIFO queue from the AWS dashboard)
