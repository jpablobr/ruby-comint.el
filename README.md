ruby-comint.el
==============

## Execute Inline Ruby

This minor mode exists to allow [Emacs](http://www.gnu.org/software/emacs/) to execute ruby processes dumping the results into a compilation buffer.  Useful for executing tests and the like.

## Functions:

     ruby-compile-file
     ruby-compile-region

## Installation:

In your emacs config:

    (add-to-list 'load-path "~/.emacs.d/load/path/ruby-comint.el")
    (require 'ruby-comint)

## TODO:

   - Easier way to switch between buffers.

## Note on Patches/Pull Requests:

Fork the project.
Make your feature addition or bug fix.
Send me a pull request. Bonus points for topic branches.

## Copyright:

(The MIT License)

Copyright 2011 Jose Pablo Barrantes. MIT Licence, so go for it.

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, an d/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
