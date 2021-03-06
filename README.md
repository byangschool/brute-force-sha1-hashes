# Brute Force SHA1 Hashes
A program used to break SHA1 hashes in a brute force manner. 

Written by **Benson Yang**

Uses Python 2.7.

## Getting Started
Download Komodo IDE and make sure you are running Python 2.7.

### Downloads
Komodo IDE. Download [here](https://www.activestate.com/products/komodo-ide/download-ide/).

Python 2.7. Download [here](https://www.python.org/downloads/release/python-2715/).

(Curiosity sake)Common Password List used. [here](https://raw.githubusercontent.com/danielmiessler/SecLists/master/Passwords/Common-Credentials/10-million-password-list-top-1000000.txt)

### Running the program

Download and run SHA1.py.

**The program runs depending on the number of args.**

1 arg : Run **SHA1.py** and paste the SHA1 hash in the script arguments(Question 1 & 2).

![alt text](https://github.com/byangschool/brute-force-sha1-hashes/blob/master/singleargument.png)

2 arg : Run **SHA1.py**, however the first arg is the SHA1 hash and the second arg is the salted hash(Question 3).

![alt text](https://github.com/byangschool/brute-force-sha1-hashes/blob/master/arguments.png)

3 arg : Run **SHA1.py** and paste the SHA1 hash, with "two terms", in the script arguments(Question 4).

![alt text](https://github.com/byangschool/brute-force-sha1-hashes/blob/master/threeargument.png)

### SHA1 Hashes to Brute Force
(20pts) Testing program hash : b7a875fc1ea228b9061041b7cec4bd3c52ab3ce3

(25pts) Medium hacker hash : 801cdea58224c921c21fd2b183ff28ffa910ce31

(30pts) Leet hacker hash : ece4bb07f2580ed8b39aa52b7f7f918e43033ea1

Salt term : f0744d60dd500c92c0d37c16174cc58d3c4bdd8e

## Answers
Testing program hash : letmein

![alt text](https://github.com/byangschool/brute-force-sha1-hashes/blob/master/testingprogramhash.png)

Medium hacker hash : vjhtrhsvdctcegth

![alt text](https://github.com/byangschool/brute-force-sha1-hashes/blob/master/mediumhackerhash.png)

Leet hacker hash : harib

![alt text](https://github.com/byangschool/brute-force-sha1-hashes/blob/master/leethackerhash.png)
