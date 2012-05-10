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

1. b:json_dump
 
   this functions take a list contains line as input, output is a json string