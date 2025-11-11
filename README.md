<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This demonstration outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution
<h2>Lifecycle Stages</h2>

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/b81c8600-cd73-4921-b688-a00560218d73" />

</p>
<p>
1. As an end user, Damian, I created a ticket → Issue: "Slow performance"
</p>
<br />

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/05da0567-2662-4260-9065-ec5136a9188a" />

</p>
<p>
2. Then I assigned the ticket to myself, logged in as John.
</p>
<br />

<p>

<img width="600" alt="image" src="https://github.com/user-attachments/assets/8c2b4da5-bd3c-47a9-aa6d-f49522439e4a" />
</p>
<p>
2. Next I selected the SLA to be Sev-B. This is because the issue isn't critical, but it's affecting the user's efficiency.
</p>
<br />

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/220899ae-f980-4bc4-b04c-a454cd1f69d5" />

</p>
<p>
3. I contacted and asked the user for consent before connecting to his computer remotely using RDP(remote desktop protocol) then I ran task manager and saw there were high disk usage from the pending Windows update and drivers and background startup applications
</p>
<br />

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/c1bcbc06-04e7-410e-ad7d-5090d96b2736" />
  
</p>
<p>
4. Then I installed the Windows update and drivers. After that I disabled the unimportant startup applications within task manager. Finally I restarted the computer and verfied that the computer's performance was improved.
</p>
<br />

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/920bb611-de4c-4a65-86c4-c73016aa6207" />

</p>
<p>
5. Finally, I closed the ticket changing the status to resolved.
</p>
<br />

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/8c3a2570-0afb-460f-9ac9-c60a9bf7ba14" />


</p>
<p>
In my next ticket, a user reports that their employees can not access the backing portal. This issue clearly has a wide impact since no users could log in so I set the SLA to Sev-A since it would affect the entire business operations. Then I assigned the ticket to Jane Doe because she is in charge of the online banking department.
</p>
<br />

<p>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/f2f9c189-9b0b-41ef-97c0-f07438bfd4e5" />

</p>
<p>
I logged in as Jane Doe and found the problem was the recent Windows update so I rolled back the Windows update and contacted the vendor for a proper fix. I confirmed the online banking portal to be up and running and set the ticket to resolved.
</p>
<br />
