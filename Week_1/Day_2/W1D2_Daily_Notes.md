# Daily Notes

## Password Obfuscator challenge

### Algorithm:
  1. Get a single string as command line argument.
  2. Loop through string
  3. Apply rules.
  4. Append to result string
  5. return result string

## Function Best Practices - Introduction (Reading)

- How to name functions?:
    - A useful principle is to not add cleverness unless you are absolutely sure you’re going to need it

- It is ideal if functions try to avoid reading outer scope variables.

- Data should instead be passed in as a parameter, making it available within the function's inner scope.

## Rolling dice problem
### Algorithm:
  1. Get command line argment
  2. Generate 3 random numbers betwean 1 and 6.
  3. Append numbers to emtpy result string.
  4. Return result string.

## TypeOf vs isArray()

  The method isArray() is prefereed to typeOf() when checking for array type. This is because typeOf returns and object and isArray checks for an array specifically. TypeOf is only good when checking against other primatives.

