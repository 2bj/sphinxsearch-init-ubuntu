Sphinx Search Ubuntu Init Script
================================


Installing
----------

You might need to edit the paths in the init script to fit your own
needs, depending on how you installed Sphinx.

    $ git clone git://github.com/stockr-labs/sphinxsearch-init-ubuntu.git
    $ sudo cp sphinxsearch-init-ubuntu/sphinxsearch /etc/init.d/sphinxsearch
    $ sudo chmod +x /etc/init.d/sphinxsearch
    $ sudo update-rc.d sphinxsearch defaults

