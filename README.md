# joffice
Designers job tracking software.

This software should provide basic CRM type services for website designers.  It's NOT meant to be a full blown crm but instead something that allows easy tracking & searching of data needed/used in the process of creating a website.
Should use composer/npm libraries whenever possible.

Key goals are:
1. contacts
  - Id ( index )
  - Name ( index, search key ) 
  - phone
  - Email
  - URL site ( sites )
  - URL admin ( sites )
  - Notes
  
  
2. Designers
  - Id ( index )
  - default designer ( y / n )
  - Name ( search key )
  - phone
  - email
  - facebook
  - Notes
  - Tags
  
  
3. Sites ( multiple per contact )
  - Id ( index )
  - client ( contacts )
  - site url ( contacts )
  - admin url ( contacts )
  - master user?
  - master pw?
  - cpanel url
  - cpanel user
  - cpanel pw
  - ftp url
  - Notes
  - Snippets ( snippets )
  - Software used ( software )
  
  
4. Access
  - Id ( index )
  - Site url ( contacts )
  - Designer ( multple per site )
  - Designer site user
  - Designer site pw
  - Designer ftp user
  - Designer ftp pw
  - Notes
  
  
5. Snippets
  - Id ( Index )
  - Site ( sites )
  - Notes ( searchable )
  - Snippets ( searchable )
  - Tags
  
  
6. Software
  - Id ( index )
  - Name ( searchable )
  - url/JED Link
  - phone
  - email
  - facebook link
  - user
  - pw
  - key
  - Notes
 
 
7. Media
  - Site ( sites )
  - Usage
  - file
  - Notes
