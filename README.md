General Provisions
1.1. This Privacy Policy (hereinafter — the “Policy”) describes what data the Discord bot “Welcome Bot” (hereinafter — the “Bot”) collects, how it is used, stored, and protected.

1.2. By using the Bot or adding it to a server, you agree to this Policy.

1.3. If you do not agree with the Policy, stop using the Bot and remove it from your server.

1.4. This Policy is drafted in accordance with:

Discord Privacy Policy;

EU General Data Protection Regulation (GDPR) — for users from the EU;

Federal Law No. 152-FZ “On Personal Data” — for users from the Russian Federation.

What Data the Bot Collects
The Bot collects the minimum amount of data necessary for the new member welcome feature to work.

2.1. Data Received Automatically from Discord

Data type	Why it is needed
User ID	Mention in the welcome
Username (username, display name)	Address in the message
Avatar URL	Display in the embed message
Guild ID	Determining where to send the welcome
Channel ID	Where to send the welcome
Server join date	Generating the welcome text
Number of server members	Displaying “you are our Nth member”
2.2. Data the Bot Does NOT Collect

❌ Content of direct messages (DMs)
❌ Content of messages on servers
❌ Email, phone number, Discord password
❌ Payment data
❌ Voice data
❌ User IP addresses
❌ Data about other servers except the one where the Bot is installed

How Data Is Used
3.1. Data is used exclusively for:

generating and sending the welcome message;

displaying the new member’s nickname and avatar;

server settings functioning (for example, the selected welcome channel).

3.2. Data is NOT used for:

advertising and marketing;

user profiling;

training third-party models;

selling or transferring to third parties.

Data Storage
4.1. The Bot does not maintain a permanent user database.

4.2. Temporary storage:

data from the on_member_join event is processed at the time of the event and is not saved after the message is sent;

server settings (welcome channel ID) may be stored as a configuration file if this is provided by the functionality.

4.3. If the Bot uses a database (for example, SQLite), it contains only server and channel IDs — without users’ personal data.

4.4. Data is deleted:

automatically when the Bot is removed from a server;

at the request of the server owner;

at the request of the user themselves (see section 7).

Transfer of Data to Third Parties
5.1. The Bot does not transfer data to third parties, except in the following cases:

Discord Inc. — since the Bot operates through the official Discord API, all data is transmitted through Discord’s secure channels;

Hosting provider — if the Bot is hosted on a server (for example, a VPS) where configuration files are stored. The provider does not have access to the content of the data;

Legal requirements — if an official request is received from authorized bodies.

5.2. The Bot does not sell or rent out data.

Security
6.1. The following protection measures are taken:

data transmission via HTTPS/WSS;

storage of the Bot token in a secure environment (environment variables);

limiting the Bot’s permissions to the necessary minimum (Send Messages, Embed Links, Attach Files);

regular updating of libraries.

6.2. Despite protection measures, no method of transmitting data over the internet is 100% secure. The author cannot guarantee absolute protection.

User Rights
In accordance with the GDPR and 152-FZ, you have the right:

Right	What it means
Right of access	To find out what data of yours the Bot processes
Right to rectification	To demand correction of inaccurate data
Right to erasure	To demand deletion of your data
Right to restriction	To restrict processing of your data
Right to object	To object to processing
Right to portability	To receive a copy of your data
To exercise any of these rights, write to the contact specified in section 10.

A response is provided within 30 days.

Children’s Data
8.1. The Bot is not intended for use by persons under 13 years of age (or another minimum age established by the legislation of your country and Discord).

8.2. The author does not knowingly collect children’s data. If such a fact becomes known, the data will be deleted immediately.

8.3. If you are a parent and believe that your child has provided data to the Bot, contact the author.

Changes to the Policy
9.1. The author has the right to change this Policy.

9.2. In case of material changes:

the date at the beginning of the document is updated;

a notification is published in the support channel or in the Bot’s repository.

9.3. Continued use of the Bot after changes means agreement with the new version.

Contacts
For all questions related to data processing:

Discord: your_tag#0000 or @username
Email: your_email@example.com
GitHub: https://github.com/your_username/your_repository

Consent
By using the Bot, you confirm that:

✅ you have read this Policy;
✅ you understand what data is collected and why;
✅ you agree to the terms of data processing.
