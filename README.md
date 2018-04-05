# copyFiles

The Class CopyFilesFromDirectoryAndSubdirectoris copies all the mp3 file from the given directory(upto n level of 
subdirectories) to a target folder.

I have a directory structure in which i have some specific files (say mp3 files) organised directly or in subdirectories(upto n levels). For example:

Music Folder
  a.mp3
  folder2
    folder3
      b.mp3
  c.mp3
  folder4
  d.mp3
  folder5
    folder6
      folder7
        folder8
          e.mp3
Now, what i require is to copy all files (.mp3 file) from all the folders and subfolders into another target folder. So my target folder would be like this:

targetFolder
a.mp3
b.mp3
c.mp3
d.mp3
e.mp3


***********Solution************
The solution uses Java 9 NIO 2 library to get the desired output.
