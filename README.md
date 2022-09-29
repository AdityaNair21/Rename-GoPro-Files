# Rename-GoPro-Files
This AppleScript file will rename GoPro files to a more usable format.

# Background

If you have ever worked with GoPro files, you will know that GoPro uses a really annoying naming scheme for the files. GoPro videos are never longer than 4 GB. This is becuase a FAT32 Memory Card cant handle files larger than this. It also helps as a safety precaution, so if you loose one file, you still have alot of footage. So GoPro splits your video into several 4GB "chapters" which can later be re-integrated in any video editing software. 

The issue lies in that GoPro names these split-up files with the chapter before the file number - which makes it super annoying when you are looking at the files on a computer, and using the clips in post-production editing. The order, when sorted by name, is seemingly random. One solution is to sort by date created, which does give you the right order, but is still confusing to look at. This feature also may be abest when looking at the files in other editing softwares. 

Some people manually rename every file, which of course is far from ideal.

My solution is to to use an AppleScript to automate the process of renaming the files into something readable. 


# Prerequisite

To run this script, you need a Macbook. 
You also ideally want all the files you want to be renamed in one folder. 

# Installation
Download the [Rename GoPro Files Script](Rename-GoPro-Files.scpt) file.

# How to Use the Project
Open the Rename-GoPro-Files.scpt with Script Editor, which should come installed with any Apple Mac PC.

Click Build to complile the script:

![image](https://user-images.githubusercontent.com/30671624/193156521-11a97aff-fe67-416b-864a-9f98fa74cf74.png)

Click Run to execute the script. 

![image](https://user-images.githubusercontent.com/30671624/193156992-b3ed9b5f-1410-4396-89f4-0976799dff6a.png)


This will open Finder. From here, select the folder that your GoPro files are located, and press "choose."

All GoPro files with the old convention will be renamed with the new convention. 

Files that are already using the new convention will NOT be renamed.

# New File Naming Convention:
![image](https://user-images.githubusercontent.com/30671624/193157187-1c90432a-ed62-49a1-b174-5c68032c58aa.png)

# Old Default File Naming Convention: 
![image](https://user-images.githubusercontent.com/30671624/193157361-2a28cb85-0ba4-4655-9c24-c501ffa5e9f2.png)
