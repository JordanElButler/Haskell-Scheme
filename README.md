# About
A basic lisp interpreter written in Haskell using the Parsec libary. Following https://en.wikibooks.org/wiki/Write_Yourself_a_Scheme_in_48_Hours

# Compiling
`ghc -package parsec -fglasgow-exts -o lisp lisp.hs`

# Usage
Run the output executable `./lisp`. To load standard lib `(load "start.scm")`. To exit enter `'quit'`.