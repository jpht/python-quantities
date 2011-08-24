to install quantities, run the following in the source directory:

python setup.py install

or if you're using a debian based distroi, either :

  * run git-buildpackage from the source directory

  * or run debuild -b from the source directory (debuild -b -us -uc if you
    don't want to sign your packages)

you will then find packages in the parent directory that you can then install
through dpkg -i or debi :)
