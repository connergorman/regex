# Regex

Learning rust by writing my own regex parser.

## Part 1

To better understand finite automata, part 1 will be to encode a particular regular expression as a state machine and test accept/reject for various inputs.

### Language

Alphabet: {a, b}

The language that the state machine should accept is "a+bba+" (or eqivalently, "aa*bbaa*")
