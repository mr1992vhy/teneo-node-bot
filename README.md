# TENEO EXTENSION NODE BOT
![TRWA](assets/img1.jpg)


## Prerequisite
- Git
  ```
  sudo apt install git
  ```
  
- Node JS (v22)
  ```
  sudo apt install npm
  ```
  
- screen
  ```
  sudo apt install screen
  ```

## Join My Telegram Channel

For more bots and tutorials you can join our Telegram channel

[**UbuntuForNodes**](https://t.me/ubuntufornodes)

also you can follow me on [X(iamshaho)](https://x.com/iamshaho)


## TENEO EXTENSION NODE 

### in order to use this bot you should register to Teneo with my REF code which is ```0CH20```


➡️ Download Extension : https://chromewebstore.google.com/detail/teneo-community-node/emcclcoaglgcpoognfiggmhnhgabppkm
- Install Extension
- Login / Create Account
- Enter Ref Code : ```ngGtG```  (USE REF GOT 2500 Points)
- Verify Email
- Run Nodes Extension


## Setup & Configure BOT

### Linux
1. Clone project repo
   ```
   git clone https://github.com/mr1992vhy/teneo-node-bot.git && cd teneo-node-bot
   ```
2. Run
   ```
   npm install && npm run setup
   ```
3. Configure your accounts
   ```
   nano accounts/accounts.js
   ```

4. Configure the proxy ( optional )  **USE PROXY IF YOU RUN MULTIPLE ACCOUNTS**
   ```
   nano config/proxy_list.js
   ```
5. Run Bot

   ```
   screen -S teneo
   ```
   
   ```
   npm run start
   ```

   Ctl + A + D
   
### Windows
1. Open your `Command Prompt` or `Power Shell`.
2. Clone project repo
   ```
   git clone https://github.com/TheShaho/teneo-node-bot.git && cd teneo-node-bot
   ```
3. Run 
   ```
   npm install && npm run setup
   ```
5. Navigate to `teneo-node-bot` directory. 
6. Navigate to `accounts` folder and rename `accounts_tmp.js` to `accounts.js`.
7. Now open `acccounts.js` and setup your accounts.
8. Navigate to `config` and adjust the `config.js` as needed.
9. Also Configure proxy if you want to use proxy, by open `proxy_list.js`. (if you have 5 accounts, proxy is required)
10. Back to `teneo-node-bot` directory.
11. To start the app open your `Command Prompt` or `Power Shell`
12. Run Bot
    ```
    npm run start
    ```


## IMPORTANT NOTE (READ IT THIS IS NOT DECORATION)

DYOR

How can I get Teneo Points?
Reward distribution varies based on your contribution. You can collect Teneo Points through connecting your Node or inviting new people to our network. The points are distributed as the following:

Invite a Friend
Points per Referral	
5,000	
Points per Invitee
2,500

Node Connectivity
Points per Heartbeat
25
Max Points per Day
2,400

*Points are credited when the invitee has 10 successful heartbeats.
**Each hour consists of 4 heartbeats that evaluate if your Node is connected and successfully running. Please note that the points model can change at any time.

Teneo Using Web Socket, so make sure you only run 1 accounts session, example if you run bot using account A, dont run account A on your browser extension.


[source](https://github.com/Widiskel/teneo-node-bot)
