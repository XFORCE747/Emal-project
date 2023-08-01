# EMail Services

#### Video Demo:  <https://youtu.be/KSUU2wmjI_I>

#### Description:

Electronic Mail (e-mail) is one of most widely used services of Internet. This service allows an Internet user to send a message in formatted manner (mail) to the other Internet user in any part of world. Message in mail not only contain text, but it also contains images, audio and videos data. The person who is sending mail is called sender and person who receives mail is called recipient. It is just like postal mail service. Components of E-Mail System : The basic components of an email system are : User Agent (UA), Message Transfer Agent (MTA), Mail Box, and Spool file. These are explained as following below.

User Agent (UA) : The UA is normally a program which is used to send and receive mail. Sometimes, it is called as mail reader. It accepts variety of commands for composing, receiving and replying to messages as well as for manipulation of the mailboxes.
Message Transfer Agent (MTA) : MTA is actually responsible for transfer of mail from one system to another. To send a mail, a system must have client MTA and system MTA. It transfer mail to mailboxes of recipients if they are connected in the same machine. It delivers mail to peer MTA if destination mailbox is in another machine. The delivery from one MTA to another MTA is done by Simple Mail Transfer Protocol.
Mailbox : It is a file on local hard drive to collect mails. Delivered mails are present in this file. The user can read it delete it according to his/her requirement. To use e-mail system each user must have a mailbox . Access to mailbox is only to owner of mailbox.
Spool file : This file contains mails that are to be sent. User agent appends outgoing mails in this file using SMTP. MTA extracts pending mail from spool file for their delivery. E-mail allows one name, an alias, to represent several different e-mail addresses. It is known as mailing list, Whenever user have to sent a message, system checks recipient’s name against alias database. If mailing list is present for defined alias, separate messages, one for each entry in the list, must be prepared and handed to MTA. If for defined alias, there is no such mailing list is present, name itself becomes naming address and a single message is delivered to mail transfer entity.
Services provided by E-mail system :

Composition – The composition refer to process that creates messages and answers. For composition any kind of text editor can be used.
Transfer – Transfer means sending procedure of mail i.e. from the sender to recipient.
Reporting – Reporting refers to confirmation for delivery of mail. It help user to check whether their mail is delivered, lost or rejected.
Displaying – It refers to present mail in form that is understand by the user.
Disposition – This step concern with recipient that what will recipient do after receiving mail i.e save mail, delete before reading or delete after reading.


<hr/>

![1](https://github.com/code50/88005445/blob/main/project/static/Email1.png)
<br/>


Email services
It is a web application using Python language, HTML, CSS and SQL database
Provides correspondence services via e-mail, such as Google, Yahoo and Microsoft services. You can register a new e-mail, log in, view sent and incoming e-mails, open incoming e-mails, and respond to them.
Registration: Create a new account and password and confirm it

- Register: Any person can register to make a new account.
- Combose: Create a new email message and choose the subject
- Sent: You can see the sent e-mails
- Inbox: You can see incoming messages and the ability to respond to them

## Tech Stack-

* Python
* Flask
* SQLDB
(Other dependancies can be found out in te requirements.txt file)

## Installation-

1] This should start a local server and you can access it on your browser.