# mailServer1

test task:
Thank you in advance for your time and efforts.

In order to understand your knowledge in the required area, we would like to ask you to perform a test tasks.
Please send an estimation (to mariia.holiachenko@itrexgroup.com) of the test task and deadline for it *
For example: "The tasks will take 12 hours and I plan to send it till April 20 by the end of the day."
* If you think that the test tasks will take you a lot of time, which you do not want to spend for it, then please write to the reasons why you think that it will take so much time to make these tasks.
Description of the test tasks

Create a simple app on the MEAN stack or any different node.js framework, which allow user to send and review emails which have been sent.
On the main page should be the list of the emails which were sent, also the “Create” button should be on the top of the page. On each item in the list user can click and will see the details about the email. Also main user can delete the email from this list.
When user click on the create button, then we display the pop-up window (or open the separate page, you can choose any method), in which there are 2 inputs - “To” (it should be validation for email) and “Subject” (validation - this input cannot be empty), textarea - “Body”, this will be the body of email and button “Send”, which should send the data to the server and server will send the email to the “To” user. Also this email should be stored in the database, so the main user can in any time check it.
Requirements to the code:

General
Front and back part should communicate with each other using WebSockets
Data should be stored in the MongoDB
For sending the emails you can use Gmail or any different free smtp service
For the front html mock-ups you can use the Bootstrap framework
For the front logic you need to use any JS framework like Backbone, Angular, React (jQuery is not a JS framework).
As a plus will be:
Implement the authorization with login form
Store session in redis or mongodb


To run app: node server
To send email input correct gmail login/pass
