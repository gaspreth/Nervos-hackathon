1. A screenshot of the console output immediately after you have successfully issued a smart contract call.

![issue](./issue.png)

2. The transaction hash from the console output (in text format).

```
0xb15294ec1ef369455dccbdec9efb452ff886b950644523457c742078c01d8b2d
```

3. The contract address that you called (in text format).

```
0xF6ad0ef4Ab23FD003Be2132E4cF981c4FC36e34A
```

4. The ABI for contract you made a call on (in text format).
```json
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
```