# zomantum-frontend-chat
Chat App (Front-end) using React.JS. (Assignment)

## Developed By - 
**Deeptanshu Sharma**

**Jaypee Institute of Information Technology, Noida**

**Major Skills** - React.js, Node.js, Express.js, MongoDB, Sass/Scss, Bootstrap, Python, Linux. 

## Live Application url -
## https://deeptanshu15.github.io/zomantum-frontend-chat/

This URL has the application deployed in. You can visit this URL to see my **Application live**.

View The Application in **Desktop/Laptop** as I haven't made it mobile friendly yet.

I have also included **ScreenShots** and **ScreenCast Videos** in the repository for your reference.

## App ScreenShots - 

![alt text](https://raw.githubusercontent.com/Deeptanshu15/zomantum-frontend-chat/master/ScreenShots%20Chat%20App/Welcome-Page.png)

![alt text](https://raw.githubusercontent.com/Deeptanshu15/zomantum-frontend-chat/master/ScreenShots%20Chat%20App/Chat-Area-with-Another-contact.png)

## App Highlights -
A chat app frontend where user can view contacts and select contacts by clicking on them to start a conversation. 

App has a dedicated Chat Area on right side where user can view conversation with the currently selected contact. 

**I have also included the functionality to append messages for each user when you click on the send message button in currently active conversation. (as mentioned in the assignment)**. user can switch between conversation and can view or send messages to the corresponding contact.


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Prerequisites - 
**Install NodeJS**

Refer to https://nodejs.org/en/ to install nodejs

**Install create-react-app**

Install create-react-app npm package globally. This will help to easily run the project and also build the source files easily. Use the following command to install create-react-app - 

> **npm install -g create-react-app**


## To Run Application in local -
1. Clone the project
2. Install all npm packages by Going into the project folder through terminal, and typing command - 

> **npm install**

3. In order to run application type the following command in the same directory - 

>**npm start**

The Application Runs at **localhost:3000**

## Application Design - 
The app is the top component, Which has Contacts and Chat component.

Chat component maintains logic for chat display and composing and sending messages(appending to message list).

The Contact Component maintains user's contacts(displaying and selecting contact to chat).

Other components such as ChatArea , People receive props from parents.
