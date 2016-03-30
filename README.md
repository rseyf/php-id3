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

License
-------
This product includes PHP software, freely available from <http://www.php.net/software/>
Licensed Under PHP License
  

Now you can use php-id3 functions inside of your code .
Follow me if you like music-based codes..
Happy coding ;) 
