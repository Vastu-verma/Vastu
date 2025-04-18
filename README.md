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
Java feature

2.Display total registered users:retrieves how many users are currently registered
added code :

const [totalRegistered, setTotalRegistered] = useState(0);

setTotalRegistered(peopleData.length);

console.log("Total registered users:", totalRegistered);
![image](https://github.com/user-attachments/assets/f60abccb-92d5-4731-88dd-9ca394e3237f)

