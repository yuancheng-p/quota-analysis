quota-analyse
=============


Motivation
----------
TODO


Usage
-----

1. The easiest way to use the scrypt ``quota-analyse`` is to copy it on your home directory then::

      $> python quota-analyse

   By default, the script will analyse from your current directory with a depth
   of one and print the top 20 largest directories.


2. To gather more information, you can enter the number of top largest
   directories that you want with ``-n``, the depth of directories to analyse with ``--depth``, and the
   specified directory begin to analyse with ``-d``.
   For exemple, to analy from the current directory with a depth of 3 and to
   print the top 30 largest directories::

      $> python quota-analyse -d . -n 30 --depth 3

I wish this little tool could solve your quota problem!
