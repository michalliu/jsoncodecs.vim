jsoncodecs
==========

json library in vim script

Install
----------

Copy jsoncodes.vim to __vimfiles/plugin__ of your Vim installation

Usage
----------

Use __g:loaded_jsoncodecs__ to check if jsoncodecs is loaded

    if exists("g:loaded_jsoncodecs")
        // do what you like
    endif
    
It provide the following functions

1. b:json_dump_string
 
   This functions take a list contains lines as input, output is a valid [JSON](http://json.org/) string

2. b:json_dumplines

   A utility function print out the result from __json_dump_string__
   
         :1,$call b:json_dumplines()