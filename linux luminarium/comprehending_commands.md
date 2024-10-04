# Linux Luminarium
## Hello Hackers
### cat
flag: pwn.college{I2Hzv3QzvHQ-0v6bIPQiESHRpjM.dFzN1QDL2ETN0czW}

process: typing the command _cat flag_ into the terminal

### catting absolute paths
flag: pwn.college{sdlR26Q04_Zx8FyaKy9bvq55lu9.dlTM5QDL2ETN0czW}

process: executed the command _cat /flag_


### more catting practice
flag: pwn.college{0fR-nzlt6yfvMKpvErFxg2WpJJQ.dBjM5QDL2ETN0czW}

process: exceuted the command _cat_ with argument location given in the terminal


### grepping for a needle in a haystack
flag: pwn.college{scq2Tg4scNT7FqXOqFgJ0k7KK4x.ddTM4QDL2ETN0czW}

process: executed the command _grep pwn.college /challenge/data.txt_


### listing files
flag: pwn.college{QFDh8rZ49TWiEm8yqavkJj1tqLO.dhjM4QDL2ETN0czW}

process: 

* _ls /challenge_ to list files in /challenge
* _/challenge/renamed-file-name_

### touching files
flag: pwn.college{cpeWsnN-Kc9Nwl8DND0UuDOR2DS.dBzM4QDL2ETN0czW}

process: 

* _cd /tmp_
* created both files by _touch_
* _/challenge/run_


### removing files
flag: pwn.college{UruXChdXlQMH2XwzHj6ZBTTdNet.dZTOwUDL2ETN0czW}

process: 

* _ls_ to list the files
* _rm delete_me_
* _/challenge/run_


### hidden files
flag: pwn.college{AtGT6iYnQ757jLLHjA7VwDvU2BW.dBTN4QDL2ETN0czW}

process: 

* _cd /_
* _ls -a_
* _cat flagfile_
  

### an epic filesystem quest
flag: pwn.college{odKBZMRl4DJBXMNUcL04IF--esf.dljM4QDL2ETN0czW}

process:

* _cd /_
* _ls_
* spent a lot of time using _ls_ and _cd_for every file in /
* _ls -a_
* got a clue and then _cd_ to the file
* followed the clues


  ### making directories
  flag: pwn.college{Qbynxhj8xRKqxdEt1-tG1YnAtf4.dFzM4QDL2ETN0czW}

  process:

  * _cd /_
  * _mkdir /tmp/pwn_
  * _cd /tmp/pwn_
  * _touch college_
  * _challenge/run_
 

### finding files
flag: pwn.college{M5VHWJOtHhaSULO3suGddcevGXu.dJzM4QDL2ETN0czW}  

process: 

* _cd /_
* _find -name flag_
* using _cat_ on the found files



  ### linking files
  flag: pwn.college{sLmbw1yNBqoEgyUv3PFKC3ndgSN.dlTM1UDL2ETN0czW}

  process:

  *  _/challenge/catflag_, didn't work
  * _ln -s /flag /home/hacker/not-the-flag_
  
  
