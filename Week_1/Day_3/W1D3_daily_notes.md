# Wk1D3 Daily Notes

## Objects

- When referencing an attribute of an object using [] we must use a string or else it would be referenced as a variable.

## Implementing countOnly in Lotide Challenge
  - AssertEquals only compares primitives and objects are not primitives.
  - Referencing an attribute that doesn't exist will return undefined and not an error.

## Implementing findKeyByValue in Lotide challenge
  - If you are comparing with ==, it will convert types to be the same.
  eg
  ```
  "1" == 1 //asserts to true
  "1" === 1 //asserts to false
  ```
