#Bro - My personal rant listener, helper, goto bot

####Why am I building this?

Frankly I want to pick my brains on how I can integrate a few cool things and make something that is useful for me.

####What cool things? How will it work?

I am going to make a command line tool called **remindmebro**. It will ask me, "what" and "when". This is going to go sit on a google doc, via sheestsu and when the time has come, it will remind me using [pynotify](https://pypi.python.org/pypi/py-notify). Let's see how far we get with this.

I could, in the future use this to download links, or automate them, torrents etc. I plan to call it **fetchitbro**. I hope this project is over in a few days though. Ha!


####remindmebro

Questions:
![This is how the questions look](https://github.com/rishigb/bro/blob/master/remindMe/firstLook.png)

Spreadsheet. Read up more on this on [sheetsu](https://sheetsu.com/)

![This is how the data structure looks.](https://github.com/rishigb/bro/blob/master/remindMe/dataStructure.png)


<s>Next step is to integrate this with pynotify or growl for mac.</s>

I found out that the above step is rather tricky to do, things don't seem to be working on the system. Hence the new path is to integrate the data with Google Calender somehow. Need to figure that out.
