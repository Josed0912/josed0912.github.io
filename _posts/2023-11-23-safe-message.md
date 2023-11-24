---
layout: default
description: App that detects spam email using AI on Gmail.
image: "/assets/images/safe-message.png"
---

![](/assets/images/safe-message.png)

### [Link to the Repository](https://github.com/WillDunw/Hackathon-SafeMessage.git)

## **Project Description**

This app was made in Bell's Geekfest Hackathon in a team of 3 as a response to the prompt: "An innovative way of implementing cybersecurity".

## **Technology Stack**

### Front-End 

The front end of the application was made using [React.js](https://react.dev/), which made the website's design responsive.

### Back-End

The back end of the app was made using [Node.js](https://nodejs.org/en/).

### External APIs

This app implements the [Google Gmail API](https://developers.google.com/gmail/api/guides) to access the user's inbox and the [OOPSpam](https://www.oopspam.com/) API to detect whether the emails are spam or not.

## **Application Functionality**

To run the application you must run the backend as well as the front end.

### Run the back end

1. Navigate to the **/safe-message/mini-backend** folder in the application.
2. Use the **node server.js** command.

### Run the front end

1. Navigate to the **/safe-message** folder.
2. Ensure you have the required node modules by using the **npm i** command.
3. Use the **npm start** command. 

Once the application is started a button *Scan Gmail* will be shown on the screen along with the app's description.

The first time you click the button, you will be redirected to the Gmail login page to enter your Gmail account and to give permission to Safe-Message to access your inbox.

You will then be redirected back to the application.

Then, you can click the button again and the app will get your latest 100 emails and give you a rating report on whether it's likely to be spam (0 being unlikely and 6 being definitely).



