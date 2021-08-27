<h1> 1- A screenshot of the console output immediately after you have successfully issued a smart contract call.</h1>

![issuing smart contract](https://user-images.githubusercontent.com/83914557/131137123-99257766-6a84-42ed-b2b2-c148dce7c6af.png)


<h2> 2- The transaction hash from the console output (in text format). </h2>

`0x832d9ce5b3341af5f35e9765095fbe6332a57d37cffc7a471ff88d714ab05abf`

<h3> 3- The contract address that you called (in text format). </h3>

`0x895E9EF5d24a566bF8420fb57B525a6685d91eEe`
  
<h4>  4- The ABI for contract you made a call on (in text format). </h4>
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


