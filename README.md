# Saltstack-Cheatsheet
A quick reference of useful saltstack commands

## sys.doc 
sys.doc is the --help of the SaltStack world

It can be run using the following syntax:

`salt 'minion1' sys.doc pkg | less`

Which will return the docs for the pkg module on minion1

To get information about the available commands a minion can run, use

`salt 'minion1' sys.list_functions pkg`

`salt '*' pillar.items`
