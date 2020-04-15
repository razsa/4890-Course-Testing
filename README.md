# 4890-Course-Testing
#### Updated code to solidity version 5

# Step 1 
Download the latest version of truffle using node

# Step 2
Create a directory to store your smart contract

# Step 3
Initialize the newly created directory

# Step 4
Create the contract and deploy

# Step 5
Commence testing
```
Courses.deployed().then(function(instance){return instance.setInstructor("address",77,"Donald","Trump");})
Courses.deployed().then(function(instance){return instance.getInstructor("address");})
Courses.deployed().then(function(instance){return instance.getInstructors();})
Courses.deployed().then(function(instance){return instance.countInstructors();})
```
