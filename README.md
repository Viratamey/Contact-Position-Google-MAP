# ContactDisplay

## Question No. 1

This assignment has three parts: download a contact file, add data to Phone Contacts using
code (not by Contact software), show the people’s positions with their names on Google
Map(you can only query the Contacts to get the data in this step). (Details below) Detail

Fetch the contact file “contact.txt” from the url:
http://www.cs.columbia.edu/~coms6998-8/assignments/homework2/contacts/contacts.txt

The data will look like

Dan dan@columbia.edu 40010787 116257324

John john@gmail.com 23079732 79145508

Daniel daniel@gmail.com 37985339 23716735

Johnny johnny@gmail.com 40774042 -73959961

Makiyo makiyo@gmail.com 36155618 139746094


Add first column to Name in the Contacts.
Add second column to Email in the Contacts.
Add third column to Mobile Number in the Contacts. (the number will be used as latitude in
the Map)
Add fourth column to Home Number in the Contacts. (the number will be used as longitude
in the Map).

You have to set up API keys in order to use Google Map API. Search on Google for more
help.

Just showing markers on Google Map is not enough to show which person in what place, so I
recommend you to use AlertDialog to show the Name of the person when you tap it.
This assignment has no restriction on what features you must use and also no restriction on
what user interface you design. As long as you can implement those three functions in code,
and demo to me that the results is correct. You are fine.

Hint
In case you cannot find mistakes for certain operations. You need to add those
user-permissions into your AndroidManifest.xml file.
<uses-permission android:name="android.permission.INTERNET"/>
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
<uses-permission android:name="android.permission.WRITE_CONTACTS"/>
<uses-permission android:name="android.permission.READ_CONTACTS"/>

Basically several buttons in the main user-interface are enough for you to show me the
correct result.

You don’t need to show Contacts inside the application. You can show me it is empty first
and then after add operation, it includes the data in the contact file.
Be sure just show those five people’s positions in the Map



# Reference:
Download and display contacts:
https://github.com/mobilesiri/JSON-Parsing-in-Android/tree/master/app/src/main/java/com/mobilesiri/jsonparsing


#Screenshots
![screenshot_20171101-010548](https://user-images.githubusercontent.com/30778983/32246262-6b34ba2c-bea4-11e7-95e9-5c9a228be878.jpg)
![screenshot_20171101-010601](https://user-images.githubusercontent.com/30778983/32246236-58b0f2da-bea4-11e7-99e1-ea644912dad9.jpg)
![screenshot_20171101-010632](https://user-images.githubusercontent.com/30778983/32246250-62158e94-bea4-11e7-978c-adfc8ee273e4.jpg)




