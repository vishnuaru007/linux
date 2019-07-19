## linux
Linux commands to refer
#commands
ls : displays list of files.
mkdir : creates a directory.

**size**
du -sh .  : total size
du -sh *  : size taken by each file
du -s *   : size taken by each file in kb
du -s * | sort -rn :  file size in desc order

**find**
find . -type f -size "+100M"

**grep**
-i case insensitive
-r reccursive
-n line no
