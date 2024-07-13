# OverTheWire : Natas Level 0

Natas teaches the basics of serverside web-security.

Each level of natas consists of its own website located at http://natasX.natas.labs.overthewire.org, where X is the level number. There is no SSH login. To access a level, enter the username for that level (e.g. natas0 for level 0) and its password.

Each level has access to the password of the next level. Your job is to somehow obtain that next password and level up. All passwords are also stored in /etc/natas_webpass/. E.g. the password for natas5 is stored in the file /etc/natas_webpass/natas5 and only readable by natas4 and natas5.



## Level 0
```json
"Username":"natas0"
"Password":"natas0"
"Url":"https://natas0.natas.labs.overthewire.org"
```
## Level 0-1
How to find Next level password its hidden in comments of html. You need to see the code in debug mode and You will found the password to next level 
<img width="1709" alt="Screenshot 2024-07-13 at 12 45 59 PM" src="https://github.com/user-attachments/assets/feba0f25-50ed-46ab-a140-9db40c8b3d73">

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

