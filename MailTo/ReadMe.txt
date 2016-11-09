MailTo by Vincent of Blackhand (D.A.Down)

Intro:
MailTo is a WoW add-on for managing your mail. The idea for it started when I got tired of typing the same set of names in the To field. EasyMail is handy for sending multiple items to the same person, but if you want a different person, then you have to delete what's there and type the new name. With MailTo, you type the name the first time, add it to your list, and then just do a couple of mouse clicks to select it from then on.

MailTo also provides a default sendee name, tracks all items emailed, lets you remotely view inboxes and see when items in your inbox will expire.

Installing:
Just unzip MailTo into your "World of Warcraft\Interface\AddOns" folder. You can create the sub-folders if they don't already exist.

Configuration:
When you first install MailTo, your sendee list will be empty except for your character name. As your other characters are seen, they will also be added. To add other players, open up the Send Mail window and type a name in the 'To' field. Then click on the menu button at the end of the field and click on the Add selection to add the name to the list. Continue to add names as desired, up to a limit of 32. If you make a mistake, you can remove a name by first selecting on the list and then clicking on the Remove selection. You can also remove all the names from the list by typing '/mailto clear' in the chat window. If you only play one character on a server, there is no point in keeping the name on the list.

The Inbox item check occurs when you close the mailbox. Each character has to check their inbox before they will appear on the inbox list. See the Options section for configuring features.

Note: A separate list is maintained for each server that you may play on.

Use:
Just open up the Send Mail window, click on the button and select the desired name from the list. When you send a mail, the sendee will be remembered and supplied as the default for the next mail (by server). When you send an attachment, it will be logged and you will be notified when it is delivered.

When the Send Mail window is open, you can right-click on an inventory item to attach it (standard window only) and shift-right-click to both attach and send. (Right-click also works in the Auction browse and auction windows.)

If someone has just sent you an item, you can be notified when it is ready to be picked up. Enter the command '/mailfrom <name> <item>' (or '/mf <name> <item>') in the chat window, where <name> is the player sending it and <item> is the name or description of the item.

List display:
While you can only bring up the MailTo list window when sending mail, you can display the list of names at any time by typing '/mailto list' (or '/mt list') in the chat window.

Log display:
The attachment log can be displayed by typing '/mt' in the chat window. The log will also be checked when you log in. If the log gets too cluttered or the delivery time gets corrupted (can happen after a patch), '/mt clear' will reset the log.

Inbox items:
When you position the cursor over an inbox item, the date the item was received will be shown in the tooltip. If it has attachments, the tooltip will be displayed for the attachments including money and the stack size (if >1). When you hold down the Control key before the mouseover, the message subject and text will be displayed if there is no attachment (reading the message text reduces the expiration time to 3 days max). The message text will also be displayed if it has already been read and there are no attachments left.

If you right-click on an inbox selection, if it has attached money or item, it will be retrieved. If it has neither, it will be deleted. This eliminates the need to open selections without a message. If there is an unread message without attachments, the first right-click will read it and a second right-click will be needed to delete it.

After you close the inbox, you can check on when your next inbox item will expire by typing '/mtex' in the chat window. For all characters on the current server type '/mtex server' and for any of your known characters type '/mtex all'. You can also just list the ones expiring within 3 days with '/mtex soon'. When you log in, you will be warned of any items expiring within 2 days. Items that are about to expire are color coded red for a short time warning (1 day) and yellow for a long time warning (3 days).

When you haven't checked you inbox for several days, you could have received new mail that MailTo isn't aware of. Eventually new mail will expired, so potential new mail is included in the expiration list when there is less than 7 days left before a possible expiration. There is also an icon for it in the /inbox window when there are no items to display.

You can check for new mail between your characters with the command '/mtn' to display mail that has been delivered but not viewed in the inbox yet. Only mail on the same server will be listed. To check on all servers, use /mtn all'. These items are also colored green in the /inbox window.

You can search for items in any of your inboxes with the command '/mtl <name>', where <name> is the name or partial name of the item to be located. All matching items will be listed for any known inbox on the current server. If CharacterProfiler is also active, all known inventory and bank items will also be searched.

Remote Inbox viewing:
You can check on what you saw in your inbox with the command '/inbox'. You can also view the inboxes of your other characters (they must have opened their mailbox first). When mail is send between your characters, it will be added to their inbox display window upon delivery. Mail from other players will not be known until you open your mailbox again unless you used the '/mailfrom ...' command.

New inbox items will be shaded green, items expiring in less than 1 day will be shaded red and items expiring in 1 or 2 days will be shaded yellow. Mousing over the items will show the details including the time until it expires. If the inbox is empty, but it has been more than 2 days since it was viewed, a '?' icon will be displayed, indicating that there may be new unviewed mail.

To view inbox of another character, click on the Select down-arrow and the drop-down menu will display a list of known characters on the current server. The number in “( )” after the name indicates how many items are known to be in their inbox and the color indicates the expiration time. Click on the character name to view their inbox.

To view inboxes on other servers, check the Server box and the drop-down menu will show a list of the known servers that you use. Mouseover the '>' arrow to see the list of characters for the selected server. Click on the character name to view their inbox.

Note (removing a deleted character): When you select the inbox of a different character, the drop-down menu will have a selection to remove that character. This will move all entries for that character including on the sendee list. If you remove the last character on a server, the server entry will also be removed.

Enhanced inventory right-click:
When the Send Mail window is open, if you right-click on an item in your inventory, it will automatically be placed in the attached item box. A second right-click will pick it up. If you do a shift right-click, it will attached it and also send it to the current sendee. You can quickly send several inventory items just by doing a shift right-click on each one.

When the Browse Auctions window is open, if you right-click on an item in your inventory, it will paste the item name in the Name edit box and clear the other search parameters. If you do a shift right-click, it will also select the proper Filter category and start the search. When the Create Auction window is open, if you right-click on an item in your inventory, it will automatically be placed in the Auction Item box. A shift right-click will split one item from a stack and move it to your main backpack before placing it for auction (there must be an empty backpack slot available).

When the Trade window is open, if you right-click on an item in your inventory, it will automatically be placed in an empty slot in the trade window.

You can over-ride these actions by holding down the Ctrl or Alt key when doing a right-click.

Options:
You can turn the delivery 'ding' on or off with '/mt ding', or turn off delivery alerts completely with '/mt alert'. The notifications at login can be toggled with '/mt login'. You can adjust the position of the MailTo button with '/mt pos <#>', where '<#>' is the number of pixels to move from the default position. 

You can also turn on or off the inventory right-click features. '/mt click' for toggling any use, '/mt auction' for toggling auction use, '/mt trade' for toggling trade use '/mt chat' for toggling chat window use and '/mt shift' for toggling use of the extra shift action.

The default expiration times can be changed with the command '/mtex <type> <#>', where <type> is the name of the timer and <#> is the number of days to change it to. For more precise times, you can specify hours by adding an 'h' to the end of the number. If you set a time to zero, it has the effect of disabling the timer, so to suppress the new mail icon in the /inbox window, you would type '/mtex icon 0'.

Received mail logging:
You can create a permanent log of items and money received from other players with the command '/mt log'. This log is on a per-character basis, so it needs to be set for each character that you want a log for. The log is in the SavedVariables folder under the player name folder and only contains the table MailTo_ReceivedLog. This table contains records which are indexed by a number representing the system time when the mail was processed.

The fields in the records are separated by commas for easy importing into spreadsheets, etc. You will need a stand-alone program (easily done in Lua) to read these records from the MailTo.lua file and write them into a plain text file for importing. The records are formatted as follows:
<sender>,<money>,<item name>,<stack size>,<subject>
The <money> field will be 0 if none was sent and the <stack size> will be 0 if there was no item.

CT_MailMod:
If you use this, the currently selected name from the Send window will be copied when you click on the MailMod tab. In most cases the inventory shift right-click feature will be more efficient than CT_MailMod. I don't plan on supporting mail logging of items send with CT_MailMod.

Commands:
Here is a summary of the slash commands for MailTo:

/inbox – toggle a window displaying the last known contents of your inbox.
/inbox return – list returnable items that you have sent to an alt.
/inbox <name> – displaying the last known contents of <name>'s inbox.
/mf <name> <item> – add a mail log entry for an item being sent to you.
/mt – list mail log entries for the current character.
/mt alert – toggles whether delivery messages are sent immediately.
/mt auction – toggles whether the inventory right-click is ignored for auctions.
/mt chat – toggles whether the chat link right-click is ignored.
/mt clear – clear the Send Mail menu list.
/mt click – toggles whether the inventory right-click is completely ignored .
/mt coin – toggles whether money display includes the coin letter.
/mt chat – toggles whether the chat link right-click is ignored.
/mt ding – toggle the delivered mail sound on or off.
/mt help – lists the defined MailTo commands.
/mt list – list the Send Mail menu names.
/mt login – toggles whether expiring and pending items will be listed at login.
/mt pos <#> – move the Send Mail menu position.
/mt shift – toggles whether the shift key is ignored on inventory right-click.
/mt trade – toggles whether the inventory right-click is ignored for trades.
/mtex – list the next inbox item to expire for the current character.
/mtex active – list the next inbox item to expire for all non-empty mailboxes.
/mtex all – list the next inbox item to expire for all characters.
/mtex icon <#> – set exp. days for inbox potential mail icon (def=28).
/mtex long <#> – set days for long exp. color of yellow (def=7).
/mtex new <#> – set days for potential new mail exp. listing (def=3).
/mtex short <#> – set days for short exp. color of red (def=1).
/mtex server – list the next inbox item to expire for all characters on this server.
/mtex soon – list the inbox items to expire soon, normally in 3 days.
/mtex soon <#> – set days for short exp. command (def=3).
/mtex warn <#> – set exp. days for login warning message (def=2).
/mtl <name> – locate all inbox and CharactersViewer items matching <name>.
/mtn – display newly delivered items on this server (not viewed in the inbox yet).
/mtn new – display newly delivered items on all servers.

Note: Using '?' as an argument to any command will list the defined arguments for that command. Adding a '?' to the end of any command argument will display the description of that command ('help?' and '??' are valid too).

Key bindings:
You can assign keys to the commands '/mailto', '/mtex active' and '/inbox' in the Main Menu Key Bindings (mod bindings are near the bottom).

Send comment to Vincent

Last update: 9/23/06
