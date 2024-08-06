# Magic Mirror Android
  
While there are many smart magic mirrors built using Raspberry Pi. We recommend using and Android tablet instead. There are many reasons for this, you can read the details in our our Raspberry Pi vs Android Tablet for your smart mirror post.
 
**Download File ⇔ [https://onsowinmu.blogspot.com/?um=2A0TbH](https://onsowinmu.blogspot.com/?um=2A0TbH)**


 
Place the mirror so that the back side is facing upwards. The back side is basically the least reflective side of the two. This is the side that will let the light go through, making it possible to see the display on the tablet.
 
Paste the vinyl onto the mirror. Make sure it lines up with the corners it was measured against. Try to smoothen it as best you can, but no need to worry about any creases or bubbles, as they will not be visible from the front. Cover the remaining part of the glass with vinyl. Cut off the excess with a knife.
 
Cut 2 strips from the remaining vinyl. Place the tablet onto the vinyl pasted glass, **making sure the charging port is facing downwards**(the bottom of the mirror). Use the vinyl strips to stick it in place. Be careful not to cover the speakers.
 
Insert the power cable into the tablet and use another piece of vinyl to stick it in place.This is important as it will prevent the tablet from being moved in case the power chord is tugged on or pulled lightly.

I used some wood I just had lying around that was left by the previous owner of the house. He used it to build shelving but it was surprisingly nice. I measured the wood and sawed down to the size I needed (The glass is 55x32cm, which is about 2112.5 inches).
 
I worked on the frame on and off for at least 3 weeks i think. I often got delayed because I needed extra bits and pieces, but I finally finished it. I ran into some trouble mounting the screen inside the frame, it was always a bit crooked, but I finally managed to get it right and fasten it into place. I also added black crafting paper around it to block out light on the sides, since the monitor is a bit smaller than the glass. I would recommend getting a piece of glass that is exactly the same size as your mirror if you want to make your life easier!
 
After I mounted the screen all that was left was mounting the electronics into place and hooking everything up.. I think it actually looks quite neat, all tucked in there. I added a white lamp cord with a on/off switch. The only annoying thing is that I always have to reach inside the mirror and press the power button to power it on.
 
I was originally going to run the mirror on an old Android TV stick I had lying around. But when I tried to boot it up I discovered it was stuck in a bootloop. I tried reflashing it, but it only worked for a few boot ups before bootlooping again so I thought to hell with it and bought a raspberry pi zero.
 
The Raspberry Pi Zero is a neat little computer. Setting it up is really easy. I installed Raspbian Jessie onto the SD card and inserted it into the computer. I then set up a few commands to start it up in kiosk mode, and directed it to my magic mirror website. I plan on installing MagicMirror2 on it in the near future, but I wanted to get it going right away so I just directed it to an already set up Magic Mirror website I run on a personal domain (myname.com/magicmirror). The script is password protected so only I can access it. This will do as a temporary solution.
 
In essence, a Magic Mirror is nothing more than a (magical?) Mirror that, in addition to performing its function -more or less- as such, allows to display information of very different types with a wide range of configuration possibilities. Although something already existed previously, the popularity of these devices, which respond to the DIY (Do it Yourself) philosophy, is due to Michael Teeuw and the enormous and active community of makers existing around the world of the Magic Mirror.
 
The magic is produced by a series of devices -with special reference to the irreplaceable Raspberry- that, cleverly camouflaged behind the glass, allow the desired effect to be achieved, combined with powerful modular software that allows you to experiment with infinite functionalities.
 
In this tutorial, I will not dwell in too much detail on the mirror construction or configuration process itself, but essentially what I intend to convey are my experiences in this regard as well as the end result. In any case, you will always find throughout this post a compilation of the necessary links to start your magical journey.
 
Well, in addition to your desire, to develop a project similar (or surely improved) to the one explained in this tutorial, a few little things, although nothing difficult to get or especially expensive:
 
There are countless posts on the Internet that explain, step by step, how to proceed in this regard, either if you want to build your brand new frame from scratch or if you choose to recycle one that you have on hand. I opted for the first option, using for the task a good handful of wooden slats (of a fairly good quality, by the way) from an old bed base that had been cornered in the storage room. The possibilities are endless in this regard, as much as your imagination. What is very important is that before you start cutting boards like crazy, be clear about what you want to do, well in your head, well reflected in some sketch. In addition, you should bear in mind that the frame that will house the Magic Mirror must have some background to be able to contain the necessary devices, You should also consider that the measurements of the same will largely depend on the measurements of the monitor or television that you plan to use. You can choose to have the mirror adjust to those measurements and that the information covers the entire surface of the glass, or, as in my case, you can choose a glass and frame larger than the screen you are going to use so that the information is displayed only in one part of the Magic Mirror, leaving the rest as a simple mirror.
 
In essence, what we need (well bought, well manufactured) is a mirror that on the one hand does, more or less, its function (it would be the face that, obviously, we would place outwards in our Magic Mirror) and that on the another allows the light of the screen that we are going to use to pass. The rest of the rear surface of the mirror that is not occupied with the monitor or TV, we must opaque it completely in order to avoid any light filtering through the glass, beyond that projected by our screen with the information we want to show. For this purpose, I simply used something as simple as black cardboard and matte electrical tape.
 
It touches the moment of entering the Software part, both of the Raspberry and of the Magic Mirror itself. Obviously, we could have started our project (and perhaps it would be the most recommended) for this more part of code and console and not for the more manual aspects discussed above but, in any case, this is already a matter of taste and what you have on hand. In short, if you have the wood, you can start with the frame and if what you have is a forgotten Raspberry, picking up dust in a drawer, it starts here. The question is to start and get excited about the project without waiting to have all the necessary elements for its development.
 
I assume that you have some knowledge on how to get started your Raspberry but when in doubt the best thing is to pull people who really know about these things and follow their steps and recommendations, point by point. In this sense and how little could I add to what others have already written as much more knowledge of cause, here I leave you the necessary links so that you can properly configure your minicomputer:
 
It is important to consider that although in the previous links you can find other alternatives, it is recommended that you install the official Raspberry (Raspbian) operating system in order to develop our Magic Mirror project. So there is no doubt about it, in this link you will find the necessary files. Keep this in mind if, as usual, you use Noobs (a quick installation tool with different operating systems to choose from) when configuring your Raspberry.
 
Finally and as you will quickly see, it is precisely at this moment when you are going to need to use the keyboard and mouse that we mentioned among the necessary, at the beginning of this tutorial, in order to configure your Raspberry.
 
Once we have properly configured Raspbian on our Raspberry, it is time to install the necessary packages for our Magic Mirror. The most recommended, as always, is to go to the original source and follow, step by step, the indicated instructions. In this regard, here I leave you the necessary links where you will find all the information to proceed correctly:
 
One of the most interesting features of the Magic Mirror in my opinion is its modular character. That is, once the basic package that already comes with default modules is installed, an immense range of possibilities opens up to install infinity of third-party modules developed by the active community around these types of projects.
 
Perhaps the most fun part of the entire project. There are countless modules developed by the community that are the ones that really, once the default modules are installed, are going to give life and personality to your Magic Mirror.
 
During these months dedicated to the construction of the Magic Mirror, I have tried infinity of modules (not all the existing ones, far from it, of course) until the end I stayed with the selection that I will relate below. Of course, this is absolutely arbitrary and the modules to install will depend exclusively on your needs, tastes and preferences. You will find all the indicated modules in the previous links, especially in the first one (3rd Party Modules).
 
Since, as I indicate, this is a very personal matter, I will limit myself to simply mentioning the modules that I currently have installed (you never know what will happen tomorrow) and I will comment on some aspect that you may consider of interest about them:
 
Well, this is not a minor issue, especially when you start accumulating modules and more modules and the available space is running out. As I have already indicated, there are solutions if your intention is to fill the Magic with modules but it is also relevant to know the different areas or regions where you can locate the information to be displayed by your modules. Most of them will tell you which is the best area to locate them although, in many cases, it will only be an optional recommendation (not in some modules that only will work correctly for you in the location that their author indicates). For all this, this simple graphic explanation of the different useful areas of your Magic Mirror when organizing the modules was very useful to me:
 a2f82b0cb4
 
