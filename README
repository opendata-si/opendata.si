Contains website for opendata.si

Install
=======

::

    git clone https://github.com/iElectric/opendata.si.git
    cd opendata.si
    virtualenv --no-site-packages .
    source bin/activate
    pip install pelican

Generate website
================

::

    pelican -s pelican.conf.py

Deploy
======

::

    rsync -avz --delete output/ <user>@<server>:/var/www/<blog>
