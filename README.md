
$ history   	# to history of commond
$ ls -lart
$ ls -lart
$ cd /var/log/
$ ls -l 		# long listing
$ ls
$ cd /var/log/  #
$ ls ltra
$ cd  			#move to home directory
$ pwd			#to see current directory
$ cd /root/
$ ls -lart /home/
$ tar -cvf logs.tar *.log lastlog faillog
$ grep error lastlog
$ grep error faillog
$ grep error dpkg.log
$ grep Error *.log
$ grep -i Error *.log
	   -i : inglore the type
$ grep -w Error *.log
       -w : w will search adject match

Notes : grep - commond is use for searching the patteran( filter the content)
 
$ find		# list down all directory
$ find -type f
$ find -type f -name "*.log"
$ find /var -type f name "*.log"
$ find / -type f name "*.log*
$ find /var -type f iname Lastlog -exec ls -lart {} \;
$ find /var -type f iname Lastlog -exec tar -cvf custom.tar {}\;
$ tar -tvf custom.tar
$ tar --help
$ sed 's|error|ERROR|g' dpkg.log 	#replace temprorlu error to ERROR|g
$ grep error dpkg.log
$ sed -i 's|error|ERROR|g' dpkg.log  #It will change paramently
$ grep -i error dpkg.log

$ touch sample.txt 	# touch commond use for creating new file
$ ls -alrt
$ cat sample.txt	# cat cpmmond get the contant of file
$ find /var/log/ -type f > sample.txt
$ cat sample.txt
$ echo "First File Contant"
$ cat sample.txt
$ echo "First File Contant" >> sample.txt
$ cat sample.txt
$ echo "First File Contant" >> sample.txt
$ cat sample.txt
$ ls -lart
$ lsb_release -a
$ lsb_release -a > release.txt
$ cat release.txt
$ vi linux.txt 		# then prass I(I for insert)
$ Esc:WQ			# (here save and quit content)
$ Esc:Q! 			# (here only quit with out save content)
close the edit mode then prass Esc:WQ ( W- for write, Q- for Quit)
$ cat sample.txt 	# to file contant we will use cat commond with file name
$ echo "HI" > program.exe
$ ls -alrt
$ ls -lart /bin/
$ ls -lart /boot/
