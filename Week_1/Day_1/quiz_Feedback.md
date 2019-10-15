# Quiz one feedback

## Scope:
  Curly braces represents a new block in which there is a different scope.

  ```
  var globalVar = 0;
  if(true){
    let globalVar = 2;
    //If log statment was in here it would be 2;
  }
  // Prints 0;
  consol.log(globalVar);
  ```