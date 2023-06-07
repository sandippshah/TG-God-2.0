
## Advance Script with Privacy Filter TG-God 2.0


 There are 50+ options in this Script. All features are described below

- Login :- Using this option you can login your telegran account
- Banfilter + remover :- This filter can remove your banned account
- spambotchecker + remover :- This option will check your account is limited or not and also can remove limited account
- Scraper :- This is normal scraper. By this scraper you can scraper more than 200k member from Groups/Channel
- Private Scraper :- This scraper can scraper members from private Group/Channel
- Daily Filter :- This filter scrapes members who are online in the last 24 hours 
- Weekly Filter :- This filter scrapes members who are online in the last 7 days 
- Scrap Admin :- This scraper can only scrape Admins in Group/Channel
- Monthly Filter :- This filter scrapes members who are online in the last 7 weeks 
- Non Active Filter :- This can scraper member Last seen a long time ago
- DeleteAlreadyMember :- This is a type of filter that can remove scraped already member in data.csv
- Set Profile Pic :- By this you can set pic on your accounts
- Delete Profile Pic :- Delete profile pic on you accounts.
- Auto Add Contact For Phone :- This can add member in you account's contacts.
- Delete Contact :- Remove all contact in your accounts
- Bulk Adder :- This can add bulk member in groups.
- Single Adder :- Add single member
- Adder :- Add from single account
- Single Joined Adder :- Add to joined group.
- Username Adder :- Add members by username
- User ID Adder :- Add by user id. You will get UserIDInvalidError if you don't follow the instructions carefully.
- Multiple Adder PC :- Add from multiple account add the same time but only for pc
- Join Group/Channel :- Join group or channel by link from bulk accounts
- Leave Group/Channel :- Leave group or channel by link from bulk accounts
- Telegran OTP Viewer :- Views telegram otp messages
- Send Message :- Send Message to Group members you can use this for promotion
- Report Spam A User :- Report A User who spam in Groups or PM/DM
- Scam Tag :- Give scam tag to scammers.
- Add the account here you want to antiban the account.
- Remove all Antiban Account.
- Get Termux/Device Info
- Exit :- Quit the script
- and many more

## Installation:- & Instructions:-

Install Termux from f-driod and Open Termux  App 

Run all the command in termux
-    
```
termux-setup-storage 
```
-   
```
apt update && apt upgrade && apt install python && pkg install git && pip install colorama && cd /sdcard && git clone https://github.com/sandippshah/TG-God-2.0 && cd TG-God-2.0 
```
[ Edit config.ini from your file manager or any third party text editor application.
All are explained here
- From Group = In this section link of group from where you want to SCRAPE member will be entered here
- To Group = In this section link of group from where you want to ADD member will be entered here
- GroupID = in this section you need to add your group id (group id will look like this -1001561952101 )
- PhoneNumber = Enter phone number here only 1 number for using 'user id adder'.
- EnterStop = No need to edit this
- StartingAccount = No need to edit this
- EndAccount = No need to edit this ]

[ Edit phone.csv from your file manager or any third party text editor application.
and add your all numbers which will be use in members adding recommendation for 15-20 accounts but u can use your biggest.]
-   
```
python3 setup.py
```
 (Then choose ( 1 ) Setup Script, After installation choose ( 2 ) Do Exit)
 -  
```
python3 god.py
```
 (Then choose 1 to login your all accounts, its start login your all telegram accounts one by one, after successful logins exit script.)
 - 
```
python3 god.py
```
 ( Then choose 51 simple scraper to scrap all group, its scrap all group members, maximum 100k, after scraping exit a script. )
 -  
```
python3 god.py
```
  ( Then choose 53 simple adder to add all members in your group, its starts adding members one by one via all logined accounts.)
  
  
Now all Process is completed.


