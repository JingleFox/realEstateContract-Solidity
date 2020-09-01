# realEstateContract-Solidity
Scenario : Implement a smart contract to transfer the property title from seller to buyer [Real Estate Industry]. <br>
1. Write the below functions in solidity (40 points) NOTE: one address can have multiple lands <br>
  A. <b>Add new property : </b> <br>Parameters: Property Id, property value, property address, property owner address (eth address) <br>Output: Mark Property Status as Pending   , Property Id, property value, property address <br>
  B. <b><i>Buy a property (change the ownership):</b></i> <br>Prereq: Verify buyer and Seller are not same, Verify the status of the property <br>Parameters: Property ID, new owner     address <br>Output: Mark new owner address as current address, change the status to sold <br>
  C. <b>Get all the property details of an address:</b> <br>Parameters: address <br>Output: List all the properties that are not sold <br>
  D. <b>Get the property details using property ID and address:</b> <br>Parameters: PropertyID, address <br>Output: Status, property value, property address <br>
  E. <b>Edit the property details:</b> <br>Parameters: PropertyID, changed values <br>Output: Changes values <br>

//will be implementing more functions in the future <br>
