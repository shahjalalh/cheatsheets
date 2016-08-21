=========
Web Tools
=========



git:
----
    ::

    $ git status
    $ git config --global user.name "Your Name"
    $ git config --global user.email you@example.com
    $ git remote add origin https://github.com/<your-github-username>/my-first-blog.git
    $ git push -u origin master


    ::

    $ git config credential.helper store
    $ git push http://example.com/repo.git

        Username: <type your username>

        Password: <type your password>


    [several days later]

    ::

    $ git push http://example.com/repo.git

    [your credentials are used automatically]


===============



Bower:
------
    ::

     Install bower
    $ npm install -g bower
     Install packages
    $ bower install <package>
     Install from bower.json
    $ bower install
     registered package
    $ bower install jquery
     GitHub shorthand
    $ bower install desandro/masonry
     Git endpoint
    $ bower install git://github.com/user/package.git
     bower install http://example.com/script.js


===============

