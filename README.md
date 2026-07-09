# linux-command-part-001
Navigation & file Management

* pwd : show current directory. // 
* full form : Print Working Directory. ## Present Working Directory.
* ex : pwd
* 
* la -la : show all files and directories in long listing format.
* full form : list all (long listing format). hidden files.
* ex : ls -la
* //  if a file or folder name starts with adot , it becomes hidden.

* cd : change directory. 
*  // change directory to the user,s home dirrectory.
*  ex : cd
*  cd ~
*  
* cd .. : change directory to parent .
* // move up one lavel to the parent directory.
* ex : cd ..
* 
* cd - : change directory to previous.
*  // go to back to the previous working directory.
*  ex : cd -
*  

* cd / : change directory to root.
*  // go to the fot directory of the system.
*  ex : cd /
*  

*  cp : copy files from one location to another.
*  full form : copy paste.
*  ex : cp file.txt /folder1
*  

*  cp -r :  copy an entire directory (folder) along with all its contents.
*  full form : copy recursive .
*  ex : cp -i folder1/ folder2/
*  

*  cp -i : prompt before overwriting an existing file during copy.
*  full form : copy interactive.
*  ex : cp -i file.txt folder/
*  

*  mv : move or rename files and directories.
*  full form : move .
*  ex : mv file.txt /folder1
*  

*  mv (rename) : rename a file or folderby keeping it in the  same location.
*  full form : move (rename).
*  ex : mv old_name.txt new_name.txt
*  

*  mv -i : prompt for confiramation before overiting an existing file.
*  full form : move interactive.
*  ex : mv -i file.txt folder/
*  

*  mv file.txt .. : move the "file,txt" file out of the current folder into the parent directory (desktop).
*  full form : move to parent directory.
*  ex : mv file.txt ..
*  

*  mv file.txt ~/Desktop/ : move the the file directory to the desktop by specifying the full path.
*  full form : move to specific path.
*  ex : mv file.txt ~/Desktop/
*  
* rm :  remove or delete files permanently.
* full form :  remove
* ex : rm file.txt
* 
* rm -r : remove a directory (folder) and all of its contents.
* full form : remove recursive
* ex : rm -r folder_name/
* 
* rm -i : prompt for confirmation before deleting a files.
* full form : remove interactive.
* ex : rm -i file.txt
* 
* cat : display file contents.
* full-form : concatanate.
* ex : cat file_name.txt
* 
* cat > : create a new file and write content into it.
* full form : concatenate redirection (overwrite).
* ex : cat > newfile.txt
* 
* cat >> : append new text or data to the end of an existing file .
* full form : concatenate redirection (append)
* ex : cat >>  existingfile.txt
* 
* cat file1.txt file2.txt : merge and display multiple files together on the screen.
* full form : concatenate multiple files'
* ex : cat file1.txt file2.txt
* 
* cat file1.txt > file2.txt : copy the entire content of file1 into file2 (overwrites file2)
* full form : concatenate redirection copy.
* ex : cat file1.txt > file2.txt
* 
* cat file1 >> file2.txt : append the entire content of file1 to the end file2.
* full form : concatenate redirection append.
* ex : cat file1.txt >> file2.txt
* 
* cat -n : show file content with line numbers for all lines.
* fll form : concatenate number
* ex : cat -n file.txt
* 
* cat -b : show line numbers only for lines that have text (skips empty lines)
* full form : concatenate blank
* ex : cat -b file.txt
* 
* cat -s : shrink multiple empty lines into just one single empty line.
* full form : concatenate squeeze blank
* ex : cat -s file.txt
* 
* cat -E : show a dollar sign at the endof every line.
* full form : concatenate end of line.
* ex : cat -E file.txt
* 
* nano : open or create a text file inside the terminal // edit text file 
* ex : nano file.txt
* 
* touch : create empty file
* full form : touch
* ex : touch file.txt
* 
* touch file1.txt file2.txt : create multiple empty files at the same time
* full form : touch multiple files
* ex : touch file1.txt file2.txt
* 
* touch file{1...10}.txt : create a sequence of numbered or lettered files instantly.
* full form : touch sequence.
* ex : touch file{1...10}.txt
* 
* touch -a : change or update only the access time (atime) of a file to the current time
* full form : touch access time
* ex : touch -a file.txt
* 
* touch -m : change or update only the modification time (mtime) of a file to the current time
* form form : touch modification time
* ex : touch -m file.txt
* 
* touch -c : check if a file exists ; if it doesn,t do not a new file.
* full form : touch no-create.
* ex : touch -c file.txt
* 
* touch -t : change the file,s timestamp to a specific customand instead of the current time
* full form : touch time
* ex : touch -t      file.txt  [ format : yyyymmddhhmm]
* 
* mkdir  : create a new empty directory (folder).
* full form : make directory.
* ex : mkdir new_folder
* 
* mkdir folder1 folder2 : create multiple directories at the same time.
* full form : make multiple directories.
* ex : mkdir folder1 folder2
* 
* mkdir -p : create nasted directories ( parent and child folder) al at once without any error.
* full form : make directory parent.
* ex : mkdir -p projects/python/codes
* 
* mkdir -m : create a new directory and set specific file permissions (like read,write,execute) right away.
* full form : make directory mode.
* ex : mkdir -m 777 public_folder
* 
* mkdir -v : display a confirmation mesage in the terminal for every directory created.
* full form : make directory verbose.
* ex : mkdir -v new_folder


