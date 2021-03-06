Painless: a Framework for Parallel SAT Solving 
==============================================

* Ludovic LE FRIOUX (ludovic@lefrioux.fr)
* Vincent VALLADE (vincent.vallade@lip6.fr) 


Content
-------
* painless-src/:
   Contains the code of the framework.
   * clauses/:
      Contains the code to manage shared clauses.
   * working/:
      Code links to the worker organization.
   * sharing/:
      Code links to the learnt clause sharing management.
   * solvers/:
      Contains wrapper for the sequential solvers.
   * utils/:
      Contains code for clauses management. But also useful data structures.

* mapleCOMSPS/:
   Contains the code of MapleCOMSPS from the SAT Competition 17 with some little changes.


To compile the project
----------------------

* In the painless-mcomsps home directory use 'make' to compile the code.

* In the painless-mcomsps home directory use 'make clean' to clean.


To run the solvers
------------------

* painless-mcomsps:
   ./painless-mcomsps dimacs\_filename

* painless-mcomsps-strength:
   ./painless-mcomsps -strength dimacs\_filename
