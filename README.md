<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Ticket Lifecycle: Intake Through Resolution
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source helpdesk ticketing system osTicket.<br/>

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop (macOS)
- Internet Information Services (IIS)

## Operating Systems Used

- Windows 10</b> (21H2)

## Ticket Lifecycle Stages

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

## Lifecycle Stages

### Stage 1. ) Intake - Creating Tickets

- Open osTicket: http://localhost/osTicket/

- Select: `Open a New Ticket`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/673114d4-4c1a-4911-b7e8-da0bf84bfcf8"><br>

- <ins>Insert the following ticket information</ins>:

  - Email Address: `Karen@osticket.com`

  - Name: `Karen Karen`

  - Help Topic: `Business Critical Outage`

  - Issue Summary: `Entire mobile online banking is down`
 
  - Ticket Details: `Customers are reporting they are getting a 404 error when browsing to online banking.`

- Click: `Create Ticket`

>**Note: *When mobile online banking is down it can lead to major loss in revenue for the company.***

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/d1feaef0-f9a3-4003-8e37-c6762317e266"><br>

***

### Step 2. ) Assignment and Communication

- *You'll need to logout of your original user login account, if you haven't already.*

- Login to osTicket as an Agent: `(User: jane.doe / jane.doe@gmail.com)`

  - The one you made in the 'Post-Install-Config` lab on [Step 6.B](https://github.com/vincentchachere/post-install-config)

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/61b97e7e-8775-40a9-b0cf-87b5d10b420d"><br>

***

- Click: The `entire mobile online banking is down` Ticket we made in the prior step of this lab (step 1)

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifecycle/assets/161680745/4b5999ab-d140-4fde-ab70-819c3e4e18f6"><br>

***

- Priority: `Emergency`

  - Type In: `Business Impacting Event`
 
  - Click: `Update`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifecycle/assets/161680745/39ec18b0-7118-40fa-ad82-2038c5173c64"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/c0730a75-c864-4f7f-8891-9afcbdedb42a"><br>

***

- Click: `Department`

  - Select: `System Administrators`

  - Details: `Sys Admins responsible for mobile banking infrastructure`
 
  - Click: `Transfer`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/36c0c3af-eef1-42fe-995b-a1434502f81a"><br>

***

- Assigned to: `Jane Doe`

  - Click: `Assign`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/a554032d-af6a-4a58-8b61-4eb41fb8eb68"><br>

***

- SLA Plan: `SEV-A`

  - Details: `Business Impacting, Critical Event`
 
  - Click: `Update`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/7e8ed40c-2af1-47b0-9c21-f46559d890f8"><br>

***

>**Note: *Make sure your ticket information matches the image below and continue to the next step.***

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifecycle/assets/161680745/b24b24ca-bde3-42cc-bab7-d5b4cd8a036e"><br>

***

>**Note: *This is where you will see the history and updates of the tickets. &darr;***

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/24eb9246-f9ab-4d37-b64f-920b9632a609"><br>

***

- Response Text Box: `Coordinating with Sys Admin Team to bring mobile banking back online.`

- Select: `Post Reply`

>**Note: *The organizaition you work for will determine the type of details you type into the description.***

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/1b17a40a-3193-423b-9bdd-201edc1fa24a"><br>

***

>**Note: *As you see, the message immediately populated inside of the ticket thread.***

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifecycle/assets/161680745/1a3d6911-74ca-4273-8af5-55dc285085b4"><br>

***

- Go Back To: The `entire mobile online banking is down` Ticket

  - *Notice that the Priorty and the Department sections have been updated.*

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifecycle/assets/161680745/ea59a152-6bc6-4abf-9cf1-f729f8339c40"><br>

***

### Stage 3. ) Working the Issue

- On the back end, Jane is working with the System Adminstrator team to resolve the issue.

### Stage 4. ) Resolution
     
- Once the issue is resolved, head back to the ticket and update the end user.

- Response Text Box: `Jerry from System Engineering found and connected a failed load balancer. Mobile banking should be back up.`

- Ticket Status: `Resolved`

- Select: `Post Reply`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/9a8e565a-0549-4171-8c0d-72dbb5d37afe"><br>

***

- The ticket should now be on the closed. As you will witness, in your your `My Tickets` Tab there are no longer any more tickets, since it has been resolved.

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifecycle/assets/161680745/ecaee293-92df-4ccb-8e5b-67e3cd53334c"><br>

- Now finally, if you go to the `Closed` Tab within your `Tickets` section, you will see the Karen Ticket that you resolved is inside of there. This lets you confim that you have succesfully resolved that ticket.

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifecycle/assets/161680745/5ae96625-a25d-4e74-9196-3f4502039d84"><br>


🎉 Congratulations! You have created and resolved your first few tickets! 🎉

☎️ For any questions, or just to connect, you can message me at: www.linkedin.com/in/vincentchachere
