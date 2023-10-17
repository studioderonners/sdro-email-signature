# Studio de Ronners Email Signature Generator

### Instructions
---

&#32;
&#32;

### Create an email signature

1. In the Apple Mail App, go to Mail > Preferences > Signatures and click on the ➕ button to create a new signature. You can add some text like “Test” to help you recognize it.

![fig.1](/src/lib/README%20-%201.png)

2. Hard close the Apple Mail App by going to __Mail__ > __Quit__ Mail (cmd + Q).

&#32;
&#32;

### Locate the signature file

3. Open the Finder, go to __Go__ > __Go to Folder__ and type: ```~/Library/Mail```

![fig.2](/src/lib/README%20-%202.png)

4. Open the folder called V9 or whatever you see in your window with the highest number (this depends on the latest update of your computer). Continue along the path: __Mail__ > __V9__ > __MailData__ > __Signatures__

![fig.3](/src/lib/README%20-%203.png)

&#32;
&#32;

### Text Editor

5. Files here have weird names, but look for the latest created (it should match the time of when you created a new signature during step 1). Open it with Text Edit: _right-click_ > __Open with__ > __Text Edit__.

![fig.4](/src/lib/README%20-%204.png)

&#32;
&#32;

### Toolkit

6. Before editing this file, you need to navigate to the [🛠 Toolkit](https://www.deronners.com/toolkit/) and select the SDRO Email Signature Generator App.

&#32;

7. In here you will find a simple editor: fill in all the necessary informations:

   - Name (& Surname)
   - Function (as stated in the studio website)
   - Phone Number
   - Availability (From - To)

   &#32;
   &#32;

   If the phone number is not filled in, the studio's phone number will be added automatically. If the availability is not filled in, Mon – Fri will be added automatically. Once all informations have been filled in, you can click on __Generate Code__.

![fig.5](/src/lib/README%20-%205.png)


&#32;
&#32;

### Replace the code

8. Select the whole code just generated and copy it.

![fig.6](/src/lib/README%20-%206.png)

9. Now back at the Text Editor file we left at [point 5](#text-editor). You can now select the text inside the ```.mailsignature``` file starting from the tag ```<body ...``` until the end, delete it and replace it with the code just generated.

&#32;

10. Now you can save the file and lock it by checking the “Locked” box that shows when you click on the file name at the top of the window.

![fig.7](/src/lib/README%20-%207.png)

&#32;
&#32;

### Enjoy your new email signature!

11. Now you can open the Mail App again and you will find the new signature available. You can delete the previous one going back to __Mail__ > __Preferences__ > __Signatures__.

![fig.8](/src/lib/README%20-%208.png)