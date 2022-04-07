# <img src="hash_logo.svg" alt="HashPEChain" height="40px"> HashPEChain


### Usage

Once installed, you can use the contracts in the library by importing them:


``` solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC721/ERC721.sol";

contract MyCollectible is ERC721 {
    constructor() ERC721("MyCollectible", "MCO") {
    }
}
```

## License

HashPEChain Contracts is released under the [MIT License](LICENSE).
