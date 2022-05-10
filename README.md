# FP_ReactJS_MailClientApplication
Fresco Play TCS ReactJS - Mail Client Application | ReactJS | Created by Ambattz | 2022 |

Routes
There should be four folders:
Inbox
Sent Mails
Drafts
Trash
Implement Routing for all the folders.
Clicking the folders should change the URL and should render the corresponding emails in MailList component.

Mail List and Mail Component
The data for mails-list should be fetched from https://localhost:8001/inbox.
Load the Mail list to store and display the list from memory.
Each mail in the list should display a greyed delete button on hovering.
Clicking the mail should display the mail details in the Mail Component.
The Mail Details should be fetched from https://localhost:8001/mails/:id for each mail.
Clicking the delete button should move the mail to the trash folder.
Note: You cannot use localhost:8001/inbox in hackerrank. It should be <Hackerrankip>-8001-<SomeURL>/inbox. Similarly for mails API. You can find the HackerrankIP once you launch your app.
  
  ComposeMail Component
Clicking on the compose button should load the ComposeMail component.
It should have two input text box and a text area for fields to, subject and body.
There must be two buttons at the bottom save and send.
To field is mandatory and should have email validation by clicking send button. Clicking Send button should move it to sent mails folder.
Clicking save will move to draft folder. No validation needed.
  
  Redux - Redux Saga
The emails are to be stored in a redux store. Use actions/reducers to load and show data.
Use react saga for async middleware - needed to call APIs with redux.
Use react-router for managing folder - inbox, sent, draft and trash. Here is a sample API format:
  
  {
  "inbox": [
     {
        "id": "1",
        "from": "ievolve@tcs.com",
        "to": "user@tcs.com",
        "time": "2018-02-24T18:25:43.511Z",
        "subject": "Remainder"
      },
      {
        "id": "2",
        "from": "idm@tcs.com",
        "to": "user@tcs.com",
        "time": "2018-02-23T18:25:43.511Z",
        "subject": "TCS - IDM"
      }
  ],
  "mails": [
     {
        "id": "1",
        "from": "ievolve@tcs.com",
        "to": "user@tcs.com",
        "subject": "Remainder",
        "time": "2018-02-24T18:25:43.511Z",
        "body": "Please complete your mandatory iEvolve course"
      },
      {
        "id": "2",
        "from": "idm@tcs.com",
        "to": "user@tcs.com",
        "subject": "TCS - IDM",
        "time": "2018-02-23T18:25:43.511Z",
        "body": "You are invited for a webex"
      }
  ]
}
  
  
  All Set!
It's time to hit the keyboard.

Click Launch to start your Hands-on in the next card.
Do Project->Install to install the dependency from package.json
Do Project->Run to start your application.
Do Project-> Test to run the test cases.
Try to clear all the test cases for a better score.
Alright, Go! Go! Go!
  So you have two apis: http://localhost:8001/inbox and http://localhost:8001/mails/<id>
  
  # FP_MiniProject_FullStackApplication
Fresco Play TCS #Mini-project for T1 Wings - Full-Stack Application | ReactJS, NodeJS | Created by Ambattz | 2022 |

## TOPICS
### Learning app - MERN stack
In this project, you will build a full-stack application using React and Node.js. In this challenge you will be creating a MERN Stack learning app, where the learners can enroll, drop and give ratings to the courses.

01 You need to follow these steps otherwise you will face some server issues even hands-On code is right. 

    Step 1: Run ---- Install
    Step 2: Run ---- Run
    Step 3: Run ---- Tests 
    
02 Do this steps before pasting code after Run Tests to check the test cases passed

## PRE-REQUISITES
* MongoDB
* Express
* ReactJS
* NodeJS

## RESULT
Test Cases passed successfully.
