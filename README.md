# realEstateContract-Solidity
Scenario : Implement a smart contract to transfer the property title from seller to buyer [Real Estate Industry]. <br>
1. Write the below functions in solidity (40 points) NOTE: one address can have multiple lands <br>
A. Add new property : Parameters: Property Id, property value, property address, property owner address (eth address) Output: Mark Property Status as Pending , Property Id, property value, property address <b>
B. Buy a property (change the ownership): Prereq: Verify buyer and Seller are not same, Verify the status of the property Parameters: Property ID, new owner address Output: Mark new owner address as current address, change the status to sold <br>
C. Get all the property details of an address: Parameters: address Output: List all the properties that are not sold <br>
D. Get the property details using property ID and address: Parameters: PropertyID, address Output: Status, property value, property address <br>
E. Edit the property details: Parameters: PropertyID, changed values Output: Changes values <br>

//will be implementing more functions in the future <br>
