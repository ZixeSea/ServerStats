## **PRIVACY NOTICE**
### Last updated: `August 9, 2020`
#### Thank you for choosing to use my bot ServerStats (“we”, “our” and "us"). We think that privacy is one of the most important things, that's why will really commit in make our bot as transparent and privacy-friendly. We will **never** sell or share your data and we only collect data that is needed to make the bot work. If there are any terms in this privacy notice that you do not agree with, please discontinue the use of our bot and our services.

#### This privacy notice applies to our bots (ServerStats#0197, ServerStatsBeta#3789, ServerStatsPremium#3256 and ServerStatsAlpha#6502) and our website (serverstatsbot.com). Our website does use Google Analytics, you can see there privacy policy [here](https://policies.google.com/technologies/partner-sites).

---

## **TABLE OF CONTENTS**
1. [WHAT INFORMATION DO WE COLLECT/STORE?](#1.-WHAT-INFORMATION-DO-WE-COLLECT/STORE?)
2. [HOW DO WE USE YOUR INFORMATION?](#2.-HOW-DO-WE-USE-YOUR-INFORMATION?)
3. [HOW CAN I SEE AND/OR DELETE STORE INFORMATION?](#3.-HOW-CAN-I-SEE-AND/OR-DELETE-STORE-INFORMATION?)
4. [WILL YOUR INFORMATION BE SHARED WITH ANYONE?](#4.-WILL-YOUR-INFORMATION-BE-SHARED-WITH-ANYONE?)
5. [HOW LONG DO WE KEEP YOUR INFORMATION?](#5.-HOW-LONG-DO-WE-KEEP-YOUR-INFORMATION?)
6. [DO WE MAKE UPDATES TO THIS POLICY?](#6.-DO-WE-MAKE-UPDATES-TO-THIS-POLICY?)
7. [HOW CAN YOU CONTACT US ABOUT THIS POLICY?](#7.-HOW-CAN-YOU-CONTACT-US-ABOUT-THIS-POLICY?)

---

## **1. WHAT INFORMATION DO WE COLLECT/STORE?**
### **A. NON-AUTOMATICALLY STORE DATA.**
#### Most of the data that the bot uses is stored after running a command (so by user interaction), everything that is stored after running a command is used to make the bot work. The main function of our bot (counting channels) requires the bot to know with channel have to be updated.

#### Currently the bot stores the following data after running some of the commands that is required to make the bot work (server ID, channel ID, custom welcome text, goal information and server settings like prefix and disabled commands). If you use the premium bot and are a Patreon it will also store data about you and this includes (user ID, donate tier, and activated servers in IDs). This is also all the data that can be deleted by you (the user). The last data that is stored after user interaction is vote data and this includes (user ID, total votes, and when you vote for the last time).

#### There is also a part that can't be deleted and it's blacklisted data and this includes (user ID, reason, by, date and if you were informed). this data can only be deleted by a staff member and is only used to protect our bot.

### **B. AUTOMATICALLY STORED DATA.**
#### There is some data that is collected and/or stored without you noticing it. This can be split into sections, preset data collection, and bot errors and logs.

#### If you add the bot and the bot is online, it will already create a preset data collection. This means that the bot will already create a collection in the database for you. This is done because we assume that if you (the user) adds the bot you (the user) will also use the main function in our bot. To speed up the command like `s/setup`, `s/counter`, and other main functions we create a preset collection that only includes the server ID.

#### The last part that the bot collects and stores are error logs, most of the time if you see an error message after running a command it's also logged in a log file. This log file could include the following (server ID, channel ID, command that was run). error logs are stored in a log file this means that there not stored in the database aside from all other data.

---

## **2. HOW DO WE USE YOUR INFORMATION?**
#### All stored data is used to make the bot work. Without channel IDs our bot would have no way to find and update them. The additional vote data and only gets created when you vote, after that it's used to check if you have permissions to use additional counters.

#### The logs that the bot makes are used to fix bugs and improve the bot. logs can also be used to work on future updates and changes.

---

## **3. HOW CAN I SEE AND/OR DELETE STORE INFORMATION?**
### **A. SEE WHAT IS STORED.**
#### To make the bot as transparent as possible you can see everything that is stored about your server. It takes the full collection out of our database and sends it in the chat, you can do this by running the `s/data` command. The `s/data` command is locked behind permissions to make sure that only people that need the data can access it (if you run it in an open channel it's not our fault that everyone can see your data).

#### Higher up staff may also have permissions to request and access data from you, this is never shared and is only used to give support.

### **B. DELETE WHAT IS STORED.**
#### All data that has been stored (blacklist data not included) can be deleted and I also tried to make it as easy as possible. If you are using the normal bot you can delete the data in 4 ways (kicking and/or banning the bot, deleting the discord server, deleting your discord account or running the command `s/reset`). If you perform one of the actions mentioned it will permanently delete **ALL** data and there is no way to get your data back.

#### If you're using the donator version of the bot you can still perform the actions mentioned above (the same actions as in the normal bot), this will **NOT** delete your donator data. If you want to remove your donator data you can stop the subscription or leave the support server (ServerStats Support), this will instantly delete all data. Not paying for the subscription will also result in the deletion of all your data.

#### Deleted data will never be added back on request, if you lose your data because you perform an action that deletes your data it's really gone. if there is a fatal error in that database or there is a problem that messes up the data, a backup could be added back that could also include your data (you can still perform the same actions to get the data deleted). If the data has to be added back from a backup it will be mentioned first so you have time to get the data deleted again.

---

## **4. WILL YOUR INFORMATION BE SHARED WITH ANYONE?**
#### No, we do not share any information and this will stay like that. It's still possible that someone sees the information if you (the user) run the `s/data` command and it's your (the person that runs the command) responsibility to run this command in a private channel.

---

## **5. HOW LONG DO WE KEEP YOUR INFORMATION?**
### **A. NORMAL USER AND SERVER DATA.**
#### All user and server data is stored as long as you use the bot. After the data is deleted all data will still be stored in a backup. Current database backups are stored for around 1 month (ServerStatsBeta and ServerStatsAlpha do not make database backups).

### **B. ERRORS AND LOGS.**
#### Most of the time error logs are stored until the problem related to the log has been fixed (so until a bot update). If you don't plan to use and/or stored the log it gets deleted on a full bot restart or full server restart (we can't give an estimated time).

---

## **6. DO WE MAKE UPDATES TO THIS POLICY?**
#### Yes, as our products and function have changes it may also bring some data store changes with it. All future changes that may be made surrounding data will be added/removed here. If we change something in here then we will notify users (the user) through our support server (ServerStats Support) and you can also find the most recent version online (on our Github). If you don't receive a notification due to you not being in the support server then this is your own responsibility.

---

## **7. HOW CAN YOU CONTACT US ABOUT THIS POLICY?**
#### You can always contact me directly through discord by DMing me (ZixeSea#1234) or joining the [support server](https://discord.com/invite/vE8qKNV) (ServerStats Support). You can also send an email to support@serverstatsbot.com (keep in mind that this could take some time to get a response).

---
