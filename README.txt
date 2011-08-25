to install quantities, run the following in the source directory:

python setup.py install

or if you're using a debian based distro, either :

run debuild -b from the source directory (debuild -b -us -uc if you
don't want to sign your packages)

you will then find 2 packages in the parent directory:

  * one containing the python module
  * one containing the documentation

that you can then install through dpkg -i or debi :)
