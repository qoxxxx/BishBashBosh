# BishBashBosh

![alt tag](https://github.com/tomhiggins/BishBashBosh/raw/master/bishbashbosh.jpg)

**What is This?**
One line to get and listen to the podcasts you want. 

**Why?**
Bloated overly feature stuffed apps with restrictive eulas and walled garden methodologies break some of what made Podcasts the joy they were always meant to be. The Podcasting method was created to make it easier to get the audio offerings you wanted to hear and to offer up your audio creations to a wider audience. 

Get the app out of the way, grab the goods and listen. **BishBashBosh**....done. 

**How To Use**
- Make a directory that will hold the podcasts when they are downloaded. 
- In that directory create a files called **podcasts.txt** that contains one podcast's rss feed url per line.  There is an example **podcasts.txt** available in this repo.  
- Then simply copy  one of the **Options** and paste it in a command line.
  - For repeated use save into a .sh file and run that instead. 
- Enjoy the Podcasts. Given the option you used the Podcasts are either being stream over your local net, are playing on your Android, or are waiting in the directory you created for you to open them up with the audio player of your liking. 


**Your Options**
Here are a few lines to get at the Podcasts you want. Each one does it in a slightly differnt way and is aimed at differing situations...

**One Line One File** - This will grab **all** the episodes currently offered in the podcasts rss feeds. 

**One Line One File Audio Server** - This will grab **all** the episodes currently offered in the podcasts rss feeds. It also opens an **local net audio server**  you control from http://machinesip:8088/ and play it on any streaming media app http://machinesip:8085/ from any device connected to your local net. 

**One Line One File One Show Per Podcast** - This will grab the **most current** epsiode offered in the podcasts rss feeds. 

**One Line One File One Show Per Podcast Audio Server** - This will grab the **most current** episodes offered in the podcasts rss feeds.It also opens an **local net audio server**  you control from http://machinesip:8088/ and play it on any streaming media app http://machinesip:8085/ from any device connected to your local net. 

**Android Termux One Line One File One Show Auto Play**  -  To be run on an Android device that has Termux installed. This will grab the **most current** episode offered in the podcasts rss feeds. It will play them one at at time on the Android device.  


**BishBashBosh** running in a Linux terminal and being controled from a web browser
![alt tag](https://github.com/tomhiggins/BishBashBosh/raw/master/bishbashboshss.jpg)

**Inspiration**
- The orignal Bash based podcatcher by Linc - **BashPodder** - http://www.lincgeek.org/bashpodder/
- **Wget Mp3Blogs**, the pre podcast lifestyle -   - http://www.veen.com/jeff/archives/000573.html
