- š Hi, Iām @Mikkimo
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Mikkimo/Mikkimo is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


pragma solidity 0.4.25;

contract Bank
{
    int bal;

    constructor() public
    {
        bal=1;
    }
    function getBalance() view public returns(int)
    {
        return bal;
    }

    function withdraw(int amt) public
    {
       if(bal < amt)
       {
           bal;
           
       }
            
       else{
           bal = bal -amt;
       } }

    function Deposit(int amt) public
    {
        bal =bal + amt;
    }}
