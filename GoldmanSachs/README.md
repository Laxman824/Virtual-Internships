# Certificate of completion 
<img src="https://github.com/Laxman824/Virtual-Internships/blob/main/GoldmanSachs/screenshots/4.png" width="600">

## Project Title
Crack the hashcode of leaked passwords online | GoldmanSachs
## Installation
```bash
sudo apt-get install hashcat
sudo apt install plocate
locate wordlist
git clone https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt
hashcat -m 0 -a 0 -o cracked.txt hashs.txt /home/laxman/Desktop/Virtual Interns/Goldman Sachs/rockyou.txt
if already passwords are cracked 
hashcat -m 0 -a 0 -o cracked.txt codes.txt /home/laxman/Desktop/VirtualInterns/GoldmanSachs/rockyou.txt --potfile-disable
```

## Screenshots

<img src="https://github.com/Laxman824/Virtual-Internships/blob/main/GoldmanSachs/screenshots/1.png" width="600">
<img src="https://github.com/Laxman824/Virtual-Internships/blob/main/GoldmanSachs/screenshots/2.png" width="600">
<img src="https://github.com/Laxman824/Virtual-Internships/blob/main/GoldmanSachs/screenshots/3.png" width="600">


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/) [![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

## Tech Stack

**Tech:** hashcat, plocate, hashing,MD5 SUM

**Goldman Sachs Software Engineering Virtual Experience Program on Forage - March
2024**

 * Completed a job simulation as a Goldman Sachs governance analyst responsible
   for assessing IT security and suggesting improvements.
 * Identified that the company was using an outdated password hashing algorithm
   by cracking passwords using Hashcat.
 * Wrote a memo for my supervisor summarizing a range of proposed uplifts to
   increase the company’s level of password protection including extending
   minimum password length and using a dedicated hashing algorithm.
