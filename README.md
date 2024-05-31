For the first step, I referred to it as public variables, and I declared a datatype called string and assigned a value named tokenName.
I set the value to "ORTEGO". Next, I declared another datatype called string and created a variable named tokenAbbrv, assigning it the value "ORTEGS". 
For the uint public totalSupply, I set the value to 0. For the mapping variable, I used mapping(address => uint) public balance;. 
This mapping allows access to the values through the mapping and lets you reassign them.For the mint function, 
I defined it as function mint(address _address, uint _value) public and updated the value for totalSupply. Lastly, for the burn function, 
I provided my code for burn functions. After that, open the Solidity compiler, click "Compile MyToken1.sol", and wait for the green checkmark to appear. 
Then, go to "Deploy and Run Transactions", find the "Deploy" button, and click it. Copy the account address, scroll down, click the arrow, and this will appear on your screen.
First, you need to paste your account address in the burn section, set the burn value to 800, and click "Transact". You will see the output. 
For minting, input the address again, set the value to 500, and click "Transact". Then, click on balance, input the address again, and click "Balance". 
You will see the balance output here. For tokenAbbrv, you will see the output here, and finally, for totalSupply, you will see the output for totalSupply here.
