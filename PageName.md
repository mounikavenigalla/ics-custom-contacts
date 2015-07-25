Hi,

i made same changes to Contacts package to allow user to use T9 in stock dialer.


Changelog
```
2012-04-02(v1.7)
- merged and build with 4.0.4 source (not compatible with 4.0.3-)

2012-03-23(v1.6)
- fixed FCs when clicked on dividers (Call Logs, All Contacts)

2012-03-20(v1.5)
- long click on contact (in dialer) shows context menu (edit, delete)
- layout changes
- some bugfixes

2012-03-15(v1.4)
- click on searched item - place call
- some bugfixes

2012-03-14(v1.3)
- added contact photo
- added recent calls (call logs) as first items in dialer
- changed sorting of found contacts

2012-02-22(v1.2)
- added more accent letters

2012-02-21 (v1.1)
- added accents for the most languages

2012-02-20 (v1)
- bugfix (FC): when dialing unknown number (not saved in contacts)

2012-02-15
- contact name and all phone numbers (HOME,WORK...) are searched by T9 algorithm
- shows select-dialog when contact has more phone numbers

2012-02-13
- only contacts with phone number are now visible in dialer and searched by T9 algorithm

2012-02-10
- bugfix (FC): dialer -> start typing -> home button -> dialer -> press on contact

2012-02-09
- added "+" and " " for dialpad key "0"

2012-01-23
- added name and phone background highlight while searching via t9
- added button for clearing number (X)
- some bugfixes

2012-01-20
- initial release
```

"prod" suffix - this is compiled with flag "user" - that means, the package is signed and with less debug info.


If you want to install it, first make a nandroid backup and then update with zip package via CWM recovery or follow these steps
```
For backup
---------
adb shell

shell@android:/ $ cp /system/app/Contacts.apk /sdcard/

For restore
---------
adb shell

shell@android:/sdcard $ su
shell@android:/sdcard # mount -o rw,remount /system
shell@android:/sdcard # cp /sdcard/Contacts.apk /system/app/
```

[CONSIDER DONATION](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=rd@shrt.cz&lc=CZ&item_name=Donation_for_kAmMa&currency_code=USD&bn=PP-DonationsBF:btn_donate_SM.gif:NonHosted)