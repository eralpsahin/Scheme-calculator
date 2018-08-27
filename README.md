# Scheme-calculator
This was a simple calculator project for an undergrad course CS305 - Programming Languages at Sabanci University


|macOS |Ubuntu|
|----------|---|
|brew install mit-scheme|apt-get install mit-scheme |

- MIT/GNU Scheme implementation guide can be found [here](http://www.gnu.org/software/mit-scheme/documentation/mit-scheme-user/) for installing on other operating systems and more.
- MIT/GNU Scheme is invoked by typing `mit-scheme`
- Load the `Calculator.scm` file and have fun with the basic calculator. To be honest, the fun part is the code not the end result. It is just a calculator for god's sake.
```
1 ]=> (load "Calculator.scm")

;Loading "Calculator.scm"... done
;Value: calculator

1 ]=> (calculator '(1 + 33 - 55 * 33 + (2 - 3 * 5) - 23 * 2))

;Value: -1840

1 ]=> (calculator '(22)) 

;Value: 22

1 ]=> (calculator '(22 - 31 + 3 * 5)) 

;Value: 6

1 ]=> (calculator '(22 - 31 + (3)))   

;Value: -6
```
