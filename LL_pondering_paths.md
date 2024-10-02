# Linux Luminarium
## Pondering Paths
### The Root
flag: pwn.college{IIXcp_VKxwtxhm2COosmQjl47li.dhzN5QDL2ETN0czW}

process: as the pwn file is saved in the root directory, the absolute path of pwn is /pwn, therfore i invoked the file by simply typing /pwn into the terminal

### Program and Absolute Paths
flag: pwn.college{sIDqD38aheCvEnbBk2D0Kbs5xjS.dVDN1QDL2ETN0czW}

process: executed the run file in the challenge directory by typing /challenge/run into terminal

### Position Thy Self
flag: pwn.college{UgrOGXb5vuHUlTPzGtFtKeO5oAq.dZDN1QDL2ETN0czW}

process: 

    * tried to execute /challenge/run but didn't work as it wasn't in the current directory
    * so had to change my directory to the right directory by typing cd /usr/share/doc
    * then executed the run file by typing /challenge/run

    
### Position elsewhere
flag: pwn.college{kJwDnd4D5s1VLkYYsLrR2qBuWN5.ddDN1QDL2ETN0czW}

process: (same as "Position Thy Self")


### Position yet elsewhere
flag: pwn.college{AmEq4RTZo5UsrFtvkojJPB0Nwxs.dhDN1QDL2ETN0czW}

process: (same as "Position Thy Self")


### implicit relative paths from /
flag: pwn.college{AmEq4RTZo5UsrFtvkojJPB0Nwxs.dhDN1QDL2ETN0czW}

process: 

    * changed directory to / by cd /
   
    * typed challenge/run


### explicit relative paths from /
flag: pwn.college{QZyq80FOdUgQf29pfNoVvGSPFO8.dBTN1QDL2ETN0czW}

process:

    * changed directory to / by cd /
    
    * typed ./challenge/run


### implicit relative path
flag: pwn.college{obgLINKaCbctepigRy3z-Zg_d6x.dFTN1QDL2ETN0czW}

process: 

     * changed directory to /challenge by cd /challenge
     
     * typed ./run


### home sweet home
flag: pwn.college{wI6wTdaqin9wdoSNYUPLs8P-vSX.dNzM4QDL2ETN0czW}

process: 

    * tried running /challenge/run, but it said it needed and argument
    
    * executed /challenge/run but with an argument ~/.
    
    * terminal said it wrote the file to the location and read it, but it showed nothing
    
    * tried several things including using mkdir, cat but nothing worked
    
    * finally tried running /challenge/run with argument ~/x with an arbitrary file x, which then gave me the flag

