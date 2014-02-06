quota-analyse
=============
This is a little tool to find out the biggest files and folders.
It is useful when your quota allocated is not large.


Motivation
----------
TODO


Usage
-----

1. The easiest way to use the script ``quota-analyse`` is to copy it on your home directory then::

      $> ./quota-analyse

   or::

      $> python quota-analyse

   By default, the script will analyse from your current directory with a depth
   of one and print the top 20 largest folders.


2. To gather more information, you can enter the number of top largest
   directories that you want with ``-n``, and the specified directory begin to
   analyse with ``-d``.
   For example, to analyse from the personal directory and print the top 30
   largest folders::

      $> ./quota-analyse -d ~ -n 30

I wish this little tool could solve your quota problem!


TODO
----
1. Improve the output information when the script is running

2. Identify the exceptions (ex: permission denied :D)

3. FIXME: the option ``-d`` is buggy
