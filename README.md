# instantbird-protocol-yappy
Assists to setup a chat account for Yappy.


To connect to Yappy via XMPP (Jabber)

Below as instructions on how to connect via Instantbird, the same information applies to other clients.

    Navigate to the settings tab on Yappy or click here
    Click the "Enable XMPP client integration" checkbox to be given your login/password for the currently selected phone on your account
    Open up Pidgin
    In Pidgin, click accounts -> Manage Accounts
    Click Add
    Set the protocol as XMPP, username as provided, password as provided, domain as 'yappy.im'
    Click on the advanced tab and change the connect server and file transfer proxies to 'yappy.im' and ensure connection security is set to 'require encryption'
    If asked to accept the self-signed certificate from Yappy.im, click Accept

When you receive a new SMSmessage, you will receive a chat from [PhoneNumber]@yappy.im

Reply to this message to SMS back or send a new message to [PhoneNumber]@yappy.im to send an SMS
