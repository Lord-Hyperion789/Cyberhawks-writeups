# Team Cyberhawks Imaginary CTF 2022: System Hardening 7
By: Shuban Pal, Will Cheng, Srijan Atti
(Hyperion#8284, Prilasey#5045, Dudeamabobby#9580)
### The Challenge
   rooReaper wasn't lying when he said that he would be back. Seems that he's infiltrated the roos' new workstation! Can you investigate and secure the system?
   The challenge is best played using VMware workstation player. However, you may be able to get it to work with other software. You will receive the flag when you reach       100 points.
### Background
   To solve this challenge, you will need to download VMware workstation 16 player. After this, you will have to upload the .vmx file  given by extracting the zipped System Hardening 7 folder provided by the challenge. This problem requires a multistep solution in which you are required to patch vulnerabilities and answer questions to reach 100. You will boot into an Ubuntu 22.04 virtual machine with a README file, Scoring Report file, and Forensic Question files on your desktop. Each vulnerability patched gives a certain amount of points based on difficulty and each Forensic Question gives you 10 points. The first action would be to read the README to see how the workstation needs to be set up. and any preferences that need to be satisfied. This challenge should be familiar if you have competed in the Air and Space Force Association's CyberPatriot competition. 

### Setup of the Desktop and Important Files
   The desktop contains 5 text files for the Forensic Questions, which each contain a question and a spot for the answer. Each Forensic Question correctly answered gives you 10 points. Then, there is a link to the README, a crucial file to work done on the system and a ScoringReport which helps you see how many points you have so far.
 ![DesktopUbuntu](https://cdn.discordapp.com/attachments/998111098559549540/998710864641269932/Desktop.png)
 
## The Good Stuff 

Here are all the vulnerabilities you had to fix in order to get 100 for the flag

### Forensic Question 1 (10pts)

### Forensic Question 2 (10pts)

### Forensic Question 3 (10pts)

### Forensic Question 4 (10pts)

### Forensic Question 5 (10pts)

### All users removed from shadow group (4pts)

### Administrator group members correct (4pts)

### Address space layout randomization enabled (4pts)
 
### Symlink protection enabled (4pts)

### TCP SYN cookies enabled (4 pts)

### Kernel pointers hidden from unprivileged users  (4 pts)

### Kernel SYSRQ key disabled (4pts)

### Disabled SSH root login (4pts)

### Disabled SSH X11 Forwarding (4pts)

### Disabled SSH password login (4pts)

### Enabled SSH public key authentication (5pts)

### Set up SSH key for user rooYay (5pts)