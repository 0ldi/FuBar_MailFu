# FuBar_MailFu + MailTo
FuBar_MailFu is a FuBar plugin to track incoming mail and AH payments, and allow you to see who you have mail from when away from the mailbox, with the catch being that it will only show who the mails are from once you have checked your mailbox.        
MailTo helps you manage your mailbox and tracks items sent. It adds a drop-down list of names to the 'To:' field of the Send Mail window. This allows a commonly used recipient to be selected in 2 mouse clicks instead of typing the name in. 

# Original creator
[Tekkub](https://www.wowace.com/addons/fubar_mailfu/)     
[Vincent2](https://wow.curseforge.com/addons/project-853/)

# Showcase
![](http://imagehost.spark-media.ru/i4/E2FD33D6-D0AE-2BD2-03DB-59CFCEE6D026.png)

# Changelog
* Added in "FuBar_MailFu" just left mouse click function of "MailTo"  
`function FuBar_Mail:OnClick()    
	MailTo_inbox('');	  
end`  

Based on `FuBar_MailFu r12212` & `MailTo 1.12` 

# Instalation
Put `FuBar_MailFu`, `MailTo`, `CmdHelp` folders to `World of Warcraft\Interface\AddOns`

# Detailed description
A separate list is kept for each server. Right-click an inventory item to attach it to your mail. When you send an attachment, a log is made of pending deliveries and you will be notified when it arrives. 

Inbox items are also monitored and you are warned when items will expire soon. You can open an inbox summary window to view all of the inbox items that any of your characters have. You can also search all known inboxes for an item name and if CharacterProfiler is loaded, inventories and bank contents will also be searched. 

I stuck in some Auction House right-click features because a lot of my mailing is AH related. 

See the README file for complete details. 

