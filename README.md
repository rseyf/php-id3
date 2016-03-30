PHP ID3 Extension
=================
A PHP Library for Editing MP3 Tags (id3) 

These functions let you read and manipulate ID3 tags. 
ID3 tags are used in MP3 files to store title of the song, as well as information about the artist, album, genre, year and track number.
Since version 0.2 it is also possible to extract text frames from ID3 v2.2+ tags.

Dependencies
------------

 Make sure you have these packages before going to Installation of the extension

  1.    gcc
  2.    php
  3.    php-devel



Installation
------------

  1. Use 'git clone' to make a copy of this repository :

        git clone https://github.com/RezaSeyf/php-id3.git

  2. Change current Directory to the id3-0.2 directory :

        cd php-id3/id3-0.2

  3. Install Everything :

        sudo phpize && ./configure && make && make test && make install

  4. Add 'id3.so' to the end of your 'php.ini' file :

       sudo echo -n "extension=id3.so" >> /etc/php.ini

  TIP1: To find your php.ini file location run : 'php -i | grep php.ini'
  TIP2: To run a command as a superuser in redhat distro run: ' su -c "echo -n "extension=id3.so" >> /etc/php.ini" '

  5. Test installation:

       php -i | grep id3

  You should see something like :  'id3 support => enabled'


@TODO
-----
If you are a php developer who is interested to improve music functions for php , there is a lot of job todo!
some of 'em:
   
  1. Developing a Full functional PHP Class for php-id3

  2. Developing a Bundle for Symfony2 with composer package
 
  3. And More... 

 
LICENSE
-------
See ``LICENSE`` for more informations By PHP Group

##NOTE:
This CODE IS OWNED BY PHP.NET ! but This repository IS NOT A PART OF OFFICIAL PHP.NET WEBSITE. its ABSOLUTLY PERSONAL!!

I have just created this repository for the personal use in my music website project and I shared it to have a document for later use on installation process. 


It Works...
-----------
Now you can use php-id3 functions inside of your code . 

See PHP-id3 Functions: http://php.net/manual/en/ref.id3.php

If you need a Composer-enabled PHP Class to handle your MP3 tag editing in PHP , take a look at Shubham Jain's amazing work here : 
https://github.com/shubhamjain/PHP-ID3 

Follow me if you like music-based codes..Have a Happy coding ;) 
