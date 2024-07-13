# OverTheWire : Natas Level 1-2

Natas teaches the basics of serverside web-security.

Each level of natas consists of its own website located at http://natasX.natas.labs.overthewire.org, where X is the level number. There is no SSH login. To access a level, enter the username for that level (e.g. natas0 for level 0) and its password.

Each level has access to the password of the next level. Your job is to somehow obtain that next password and level up. All passwords are also stored in /etc/natas_webpass/. E.g. the password for natas5 is stored in the file /etc/natas_webpass/natas5 and only readable by natas4 and natas5.



## Level 1-2
```json
"Username":"natas2"
"Password":"TguMNxKo1DSa1tujBLuZJnDUlCcUAPlI"
"Url":"http://natas2.natas.labs.overthewire.org"
```
## Level 2-3
How to find Next level password First two are easy but this one is pretty good one us need to see source code than you will found an image use its source url and then check the files directory , there you will find the login of natas 3rd password in user.txt
<br>
### Step 0
<img width="1388" alt="Screenshot 2024-07-13 at 1 09 20 PM" src="https://github.com/user-attachments/assets/492b161a-7af7-4914-9458-4f570cfb6ba6"></img>
### Step 1
<img width="819" alt="Screenshot 2024-07-13 at 1 08 02 PM" src="https://github.com/user-attachments/assets/f4405241-4cae-4906-8be7-6bae79578554"></img>
### Step 2
<img width="679" alt="Screenshot 2024-07-13 at 1 08 14 PM" src="https://github.com/user-attachments/assets/77300fbc-8375-4605-b816-13845f9102fc"></img>



## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
