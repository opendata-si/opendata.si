Contains website for opendata.si

Install
=======

::

    $ mkdir opendata.si
    $ cd opendata.si

    $ git clone https://github.com/opendata-si/opendata.si.git

    $ virtualenv --no-site-packages .
    $ source bin/activate

    $ pip install -r opendata.si/requirements.txt

Generate website
================

::

    $ cd opendata.si
    $ pelican -s pelican.conf.py

Deploy
======

::

    rsync -avz --delete output/ dogbert:/home/hruske/opendata/www/
