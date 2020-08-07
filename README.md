# Moodle Documentation
This documentation is for the bitnami application(moodle) which is running on AWS ec2 instance

## Find Application Credentials 
### Option 1: Find Credentials By Checking The System Log On The AWS Cloud Console (EC2)
    After creating EC2 Moodle instance we will get our username and password 
    of Moodle in "Action > Instance Setting > Get System Log".

(NOTE: We can see this log only once when we stop an instance we won't see it again)

### Option 2: Find Credentials By Connecting To Your Application Through SSH
    Connect to the application through SSH.
    Run the following command to see your application credentials:
`   sudo cat /home/bitnami/bitnami_credentials
`
   
   You can find more information from 'https://docs.bitnami.com/aws/faq/get-started/find-credentials/'.

## Customisation Of Application

- After log in as superuser we get "customizing this page" option on top of the right corner using this we can customize our home page.

- An administrator can change theme settings and customize in "Site administration > Appearance > Themes"
    If we want to add a new theme then we can download the theme plugin from here 'https://moodle.org/plugins/'.

- We can install, update, and delete plugins in "Site administration > Plugins" in this section.

## UPLOAD USERS

- For adding multiple users we need to create text or CSV file and we have to mention the appropriate field in the file.

- After uploading users we can create cohorts and assign a role then we can enroll multiple users in the courses and add some restrictions on them.

- We can check the permission of the particular user in "Site administration > Users > Permissions > Check system permissions".

## CATEGORIES AND COURSES

## LANGUAGE SETTING

## Transitioning to HTTPS
