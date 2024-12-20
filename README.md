<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configuration</h1>
This tutorial outlines the post-installment requirements of the open-source help desk ticketing system osTicket.<br />


<!-- <h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com) -->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Created an Admin Role
- Created a Department
- Created a new team called "Online Banking"
- Created agents Jane and John
- Created a User
- Configured SLA
- Created Help Topics

<h2>Installation Steps</h2>

<p>
<img width="968" alt="Screenshot 2024-12-18 at 5 43 45 PM" src="https://github.com/user-attachments/assets/b5aa5ba5-e572-4b4e-a56e-f1cac96e1718" />

</p>
<p>
Now that osTicket was installed, I could use it. So, the first thing I did was create a role called "Supreme Admin." It was not necessary, because the "All Access" role has the same permissions. But I wanted to be able to say I could create roles.
</p>
<br />

<p>
<img width="972" alt="Screenshot 2024-12-18 at 5 45 51 PM" src="https://github.com/user-attachments/assets/32c675ab-ee79-47f4-939e-351132aad66a" />

</p>
<p>
Afterward, I created a department called "SysAdmins." Some tickets are only viewable if you are within a certain department. So, I created one and took a picture. Just to say I could.
</p>
<br />

<p>
<img width="963" alt="Screenshot 2024-12-18 at 5 47 22 PM" src="https://github.com/user-attachments/assets/9381a940-5354-4f17-b564-6b49c56d72c0" />

</p>
<p>
Here, I created a team called "Online Banking." I will use this to assign a ticket to everyone in this team later.
</p>
<br />

<p>
<img width="971" alt="Screenshot 2024-12-18 at 5 54 58 PM" src="https://github.com/user-attachments/assets/31e6ccc7-3fd1-4009-a2ff-f1467d052132" />

</p>
<p>
Finally, I created agents named Jane and John. Jane was given the role of "Supreme Admin," just so I could make her do anything. John, however, was not given a role. Instead, I manually controlled his access. I tried "view-only" and learned that he could not change the SLA on a ticket. I tried "Limited Access" and learned that he could not assign the ticket to anyone. So, I gave him "Extended Access." This was the "Least Privilege" he needed in order to perform all the tasks I wanted for him. In short, I learned how to apply the least privilege principle.
</p>
<br />

<p>
<img width="962" alt="Screenshot 2024-12-18 at 5 58 47 PM" src="https://github.com/user-attachments/assets/0a88f57b-f5b2-4799-819e-7878ac31e11c" />

</p>
<p>
Once my agents were ready, I created a user who could submit tickets. Although, I did allow for users to submit tickets without logging on.
</p>
<br />

<p>
<img width="968" alt="Screenshot 2024-12-18 at 6 03 01 PM" src="https://github.com/user-attachments/assets/06da269a-f965-4692-86e3-96a141a36027" />

</p>
<p>
Next, I created SLA levels. Sev-A was a severe issue that had to be fixed within an hour. So, it was set to start that timer every hour of every day. Sev-B could be done in 4 hours. But it still started the counter 24/7. Sev-C was considered a normal issue and was set for normal business hours and 5 days per week.
</p>
<br />

<p>
<img width="961" alt="Screenshot 2024-12-18 at 6 09 42 PM" src="https://github.com/user-attachments/assets/b63c1bdf-5ce6-41a0-8d16-5a49a6a56818" />

</p>
<p>
Lastly, I created some help topics for a user to choose from. With all of this done, now my ticketing system was ready to use. I had the system set up, users who could submit tickets, help topics to choose from, agents, and all the tools necessary to resolve a ticket.
</p>
<br />
