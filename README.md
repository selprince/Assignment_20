# Assignment_20
Unit 20: Solidity

The contract was built using Solidity and was tried on the Kovan testnet.

The testnet address is: 0x3b3cb82b8b706757c78bd02f00B052E8e1929e04 
Please feel free to send any money my way!

There were three different tasks that I prepared:

1. **Associate Profit Splitter:**

The contract was created to accept Ether into the contract and divide the Ether evenly among the associate level employees. This will allow the Human Resources department to pay employees quickly and efficiently.

[Associate Profit Splitter Code](http://remix.ethereum.org/#optimize=false&evmVersion=null&version=soljson-v0.5.17+commit.d19bba13.js)

To work this solidity file 

2. **Tiered Profit Splitter:**

The contract was created to distribute different percentages of incoming Ether to employees at different tiers/levels. THis contract was put in place with the follwoing key point in mind:

1. Distribute different percentages
2. CEO gets paid 60%
3. CTO 25%
4. Bob gets 15%.

[Tiered Profit Splitter Code](http://remix.ethereum.org/#optimize=false&evmVersion=null&version=soljson-v0.5.17+commit.d19bba13.js)

3. **Deferred Equity Plan:**

The contract was created to structure a employee stock ownership payout. This contract was put in place with the following key points in mind:

  1. Models traditional company stock plans
  2. Automatically manage a total of 1000 shares
  3. Annual distributions of 250 shares over 4 years for a single employee

It is worthy to note that if you would like to test the code you can simply change the definition of start_time as follows:
  
  uint start_time = now - 500 days;



  To work the contract please utilize the following file:  
 
[Deferred Equity Plan Code](http://remix.ethereum.org/#optimize=false&evmVersion=null&version=soljson-v0.5.17+commit.d19bba13.js)
  
  
  
  Enjoy!
