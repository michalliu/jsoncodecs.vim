jsoncodecs
==========

standard [JSON](http://json.org/) library of vim script

Install
----------

Copy jsoncodes.vim to __vimfiles/autoload__ of your Vim installation

Usage
----------

It provide the following functions

1. jsoncodecs#dump_string
 
   This functions take a list contains lines as input, output is a valid [JSON](http://json.org/) string

2. jsoncodecs#dump_lines

   A utility function print out the result from __jsoncodecs#dump_string__
   
         :1,$call b:json_dumplines()
