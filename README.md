# youtube-dl-askme
Small bash script to ask the user what they want to download, since I have struggled to remember youtube-dl commands myself.

To make this work from anywhere, simply place it somewhere on your system. **I.e. /home/youruser/scripts/youtube-dl-askme** and create a symbolic link for the file in your **/usr/bin**

The exact steps are listed below:

**1:** git clone https://github.com/jacobkri/youtube-dl-askme.git  
**2:** sudo ln -s ~/scripts/youtube-dl-askme.sh /usr/bin/youtube-dl-askme  
**3:** sudo chmod ugo+rx /usr/bin/youtube-dl-askme  

**Note.** the above **chmod** is the "readable" way to say:
  grant Read (r) and Execute (x) permission to User (u), Group (g), and Others (o)

You may want to only grant permissions to the user and group (ug), depending on your situration.

To download a video, simply type **youtube-dl-askme** into a terminal window. This will ask you if you want to download the video, or if you just want to download the audio (converts to mp3).
