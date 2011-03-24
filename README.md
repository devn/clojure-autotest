# By Tom Crayford #
# Preserved for posterity #

See: http://www.tcrayford.net/2009/12/08/Lein-Autotest.html

## Clojure Autotest ##

I’ve been doing a lot of testing for a clojure side project recently, and got envious of Ruby people having nice tools. In particular I liked the coloured output and automatic test running from rspactor.

I found watchr and came up with this script, which simply watches for changes to .clj files in /src and /test and runs lein test in the shell window.

To get started, install `watchr`

`gem install watchr`
and run the script in the home directory for your Leiningen-backed clojure project.

`watchr /path/to/script`
The script also does some (very basic) red/green colouring of outputs using zsh color codes.
