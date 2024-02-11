# IAM-Service-in-AWS

- ### **Steps for IAM services:**

 - Access AWS console and go to IAM service
 - Under Access management, Click in "Users", then "Add users". Insert the User name **luxxy-covid-testing-system-en-app1** and click in **Next** to create a programmatic user.
 - On Set permissions, Permissions options, click in "Attach policies directly" button.
 - Type **AmazonS3FullAccess** in **Search**.
 - Select **AmazonS3FullAccess**
 - Click in **Next**
 - Review all details and click in Create user

- ### **Steps to create access key:**

  - Click on the user you have created.
  - Go to Security credentials tab.
  - Scroll down and go to Access keys section.
  - Click on Create access key
  - Select **Command Line Interface (CLI)** and **I understand the above recommendation and want to proceed to create an access key** checkbox.
  - Click Next
  - Click on Create access key
  - Click on Download .csv file
  - After download, click Done.
  - Now, rename .csv file downloaded to **luxxy-covid-testing-system-en-app1.csv**
