### TLDR
compound is:
* a place to trade the *time value* of assets

to quantify time, 
* interest rates bring together people with idle assets and people with the ability to put them to work
  
to
* make borrowing easy and incentivize holding.

### The Rules
1. assets are organized in pools--one for each unique ethereum asset 
2. interest rates are dynamic--determined algorithmically based on supply and demand
   
    * to incentivize liquidity, interest rates increase when demand to borrow an asset is high or when supply is low 
    * interest rates decrease when demand to borrow an asset is low or when supply is high
3. everyone (lenders and borrowers) interact directly with the smart contract
   
    * users deposit assets and earn interest
    * users borrow assets by using deposited assets as collateral

4. when a borrower is borrowing more than the allowed amount, anyone can pay the borrowed asset at a lower market price and claim the borrower's collateral 

    * when the price of an asset fluctuates, the value of a user's collateral can decrease or the value of a borrowed asset can increase, causing the borrower's balance to exceed their borrowing capacity
    * borrowing capacity = value of deposited asset * collateral factor
    * collateral factor: number from 0 to 1 that represents what percent of the asset value may be borrowed










