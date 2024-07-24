# ReachInBox-Frontend Assignment

## Overview
This repository contains the code for the Reachinbox Frontend Assignment, implemented using React with TypeScript, as part of an assignment given by Reachinbox.

## TechStack Used ( Frontend )
  - Typescript
  - React
  - Tailwind css


## Demo Video :- 
https://www.loom.com/share/b12a1f9ab67e48ae8e90efff18bccc9b?sid=6a306c49-9d1a-4b37-9dfa-21b4538e3831

## Login Page

(![login page](<reachinbox/src/assets/Login Page.png>))

## Landing Page

(![landing page](<reachinbox/src/assets/Landing Page.png>))

## Dashboard with Light Mode
 
(![Dashboard light](<reachinbox/src/assets/Dashboard with Light mode.png>))

## Dashboard with Dark Mode

(![Dashboard dark](<reachinbox/src/assets/Dashboard with Dark mode.png>))

## Delete Email 

(![Email](<reachinbox/src/assets/Delete mail.png>))



 # How to Run Application on loacl system <br/>
 
   <h2>Installation</h2>
   
   Clone the repository:   ``` git clone https://github.com/vinodkr09/ReachInbox-Frontend-Assignment.git  ``` <br/>
   Navigate to the project directory:   ``` cd reachinbox ``` <br/>
   Install the dependencies:   ``` npm install ``` <br/>
   Start the development server:   ``` npm run start ``` <br/>
   Open your browser and visit:   ``` http://localhost:3000 ``` <br/>
   

   ## Features 
   
  - Authentication
  - Get Emails
  - Post Email
  - Delete Email


   <h2>Endpoints</h2>
   <h3>All Emails</h3>
   <pre><code>GET {{baseurl}}/onebox/list </code></pre>

   <h3>All Emails from Onebox</h3>
   <pre><code>GET {{baseurl}}/onebox/messages/:thread_id </code></pre>

   <h3>Add Onebox Mail</h3>
   <pre><code>POST {{baseurl}}/onebox/reply/:thread_id </code></pre>

   <h3>Delete Email</h3>
   <pre><code>DELETE {{baseurl}}/onebox/messages/:thread_id </code></pre>

 
   
