# Ada Library Wishlist
Wishlist for Ada programming language libraries, something you would like to see available in Alire - Ada Library Repository. Ordered in increasing effort level. First ones are relatively more easy and so on.

Submit your's to me by email (heharkon@iki.fi) or by PR. 

## Level 1 - Existing Ada libraries without Alire packaging

* Better Command-line argument parsing https://github.com/jhumphry/parse_args (see below)
  * This library possibly unmaintained
  
## Level 2 - Ada bindings and packaging for existing libraries

* GIF animation encoding, binding of https://github.com/lecram/gifenc for example

## Level 3 - Novel Ada code  and packaging

* Better argument parser library
  * One existing candidate https://github.com/jhumphry/parse_args 
* Cross-platform tab-completion
* Less verbose (to write) unit testing, i.e. tests based on naming conventions for example
* Maybe, Result, and Either types 
  * Comments from Alejandro R Mosteo:
    * You need definite/indefinite alternatives if you don't want to default to heap use.
    * The moment you need to map between types, dot notation doesn't work
* A library to generate semantic version comparisons between .ads files to provide information about "this really is a major bump" or "this is a minor bump"