DokuWiki docker container
=========================


To run image:
-------------

docker run -d -p 80:80 --name my_wiki mprasil/dokuwiki 

You can now visit the install page to configure your new DokuWiki wiki.

For example, if you are running container locally, you can acces the page 
in browser by going to http://127.0.0.1/install.php

Build your own
--------------

docker build -t my_dokuwiki .