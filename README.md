# Rename-GoPro-Files
This AppleScript file will rename GoPro files to a more usable format.

# Background

If you have ever worked with GoPro files, you will know that GoPro uses a really annoying naming scheme for the files. GoPro videos are never longer than 4 GB. This is becuase a FAT32 Memory Card cant handle files larger than this. It also helps as a safety precaution, so if you loose one file, you still have alot of footage. So GoPro splits your video into several 4GB "chapters" which can later be re-integrated in any video editing software. 

The issue lies in that GoPro names these split-up files with the chapter before the file number - which makes it super annoying when you are looking at the files on a computer. The order, when sorted by name, is seemingly random. One solution is to sort by date created, which does give you the right order, but is still confusing to look at. Some people manually rename every file, which of course is far from ideal.

My solution is to to use an AppleScript to automate the process of renaming the files into something readable. 


# Prerequisite

To run this script, you need a Macbook. 
You also ideally want all the files you want to be renamed in one folder. 

# Installation
Simply install the 
