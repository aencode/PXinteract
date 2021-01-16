# PXinteract
Execute and Interact With Programme or Commands using Python

``
PXinteract.py

Interact with subprocess send stdin in a list and receives stdout & stderr.

USAGE example,

from PXinteract import interact
op=interact(cmd,inp_list=[],stream=1)
``
#inp_list will be sent in STDIN one by one
#stream can be 1 , 2 or 3
#1 is for STDOUT
#2 is for STDERR
#3 is for [STDOUT,STDERR]
