# GoPhish

### GoPhish Phishing Simulation Guide

1.  **Install GoPhish**
    -   Go to the GoPhish GitHub page.
    -   Download the version that matches your operating system.
    -   Extract the downloaded file to a folder of your choice.

2.  **Run the GoPhish program**
    -   Open your terminal, command prompt, or PowerShell.
    -   Execute the GoPhish file (e.g., gophish.exe for Windows, or ./gophish for Mac).
    -   Be sure to note the URL where the admin panel is hosted.

3.  **Access the Admin Panel**
    -   Open a web browser and navigate to the admin panel URL.
    -   Log in using the default credentials.
    -   Update the password immediately for security.

4.  **Configure SMTP settings**
    -   Go to the "Sending Profiles" page and create a new profile.
    -   Enter the SMTP server details (e.g., Gmail, Mailtrap, or a custom server).
    -   Test the connection to ensure that emails can be sent.

5.  **Create a Phishing Email Template**
    -   Navigate to the "Email Templates" page and select "Create new template."
    -   Write a realistic phishing email with a sneaky link (call to action).
    -   Save the template for future use.

6.  **Create a Fake Landing Page**
    -   Go to the "Landing Page" tab and create a new page.
    -   Import a login page to make it look credible.
    -   Enable "credential capture" to log any credentials entered by users.

7.  **Add Targeted Users**
    -   Go to "Users and Groups" and create a new group.
    -   Add test users by entering their email addresses.
    -   Save the group for later use in the campaign.

8.  **Initiate the Campaign**
    -   Navigate to "Campaigns" and select "Create new campaign."
    -   Choose the email template, landing page, sending profile, and user group.
    -   Set the launch time and start the campaign.

9.  **Monitor Campaign Results**
    -   Watch the dashboard to check your campaign's performance.
    -   Analyze metrics like email open rates, link clicks, and entered credentials.
    -   Note the users who fell for the campaign.

10. **Provide Training**
    -   Download the results from your campaign.
    -   Contact those who failed and teach them what to look for.
    -   Repeat simulations down the line to see who has learned from their mistakes.
    
