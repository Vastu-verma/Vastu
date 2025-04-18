Solidity Feature
Question 2 Check if a user is registered.
function isRegistered(address _addr) public view returns (bool) {
    for (uint i = 0; i < registeredPeople.length; i++) {
        if (registeredPeople[i] == _addr) {
            return true;
        }
    }
    return false;
}
