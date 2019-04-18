# Smart_Contract_Courses
Courses is a smart contract created to understand mappings and structs in solidity. It is compatible to solidity version 0.5.0.

## Compile and Deploy this contract
1. clone the repository in your local computer using following command
```bash
$ git clone https://github.com/aarohiS/HelloWorld.git
```
2.  Download Ganache (https://truffleframework.com/ganache).
> This allows us to have our own local Blockchain.

3. Go to the project directory and run this command from command line
```bash
$ truffle migrate --reset
```
This will successfully deploy the contract on ganache.

## Testing the contract 
1. Go to Remix IDE (https://remix.ethereum.org).

2. Add the contract named Courses.sol from your local computer

3. Compile the contract Courses.sol with compiler version-
   Current version:0.5.1+commit.c8a2cb62.Emscripten.clang 
   
4. Once compiled, go to 'Run' tab and set following values for specified boxes
   Environment - JavaScript VM
   leave Account, Gas limit and Value as is.
   
5. Click on highlighted button 'Deploy'

6. Click on the deployed instance of Courses and start testing for each function.
    ### a. SetInstructor function
        copy the address of current account from Deployed contracts tab. 
        Pass following values in box next to setInstructor funtion tab.
        *copied address*, 23, Aarohi Savaliya
        Clicking on setInstructor button will output following
        
    ### b. getInstrutors function
         click on getInstructors tab and it will return following:
         
    ### c. getInstructor function
         Pass following value to this function
         *copied address*
         It will give following output
         
    ### d. countInstructors function
         click on countInstructors tab and it will return following:

              
        
