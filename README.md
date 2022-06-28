# Solidity Notes

## Hello World
- license of code: spdx as a comment
- not required, but warns during compilation
```js
// SPDX-License-Identifier: MIT

// SPECIFY TARGET COMPILER VERSION
// target specic version (BEST PRACTICE)
pragma solidity 0.8.7;
// target greater than or equal the specified version
pragma solidity ^0.8.7;

// create a contract, same as file name
contract HelloWorld {
  // public - read access to code after deployment
  string public text = "Hello World";
}
```

## Data Types
### 2 Types
- Values - 
- References - 



