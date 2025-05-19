# IPFS DOWNLOAD STEP
🔹 Step 1: Go to the official website Visit: https://docs.ipfs.tech/install/ipfs-desktop/

🔹 Step 2: Download IPFS Desktop Choose the right version for your operating system:

Windows .exe

🔹 Step 3: Install it Windows: Run the .exe and follow the installer.

🔹 Step 4: Run IPFS Desktop Open the app — it will start the IPFS daemon and give you a friendly GUI to interact with your node.

Windows: Add the ipfs.exe directory to your system's PATH environment variable.

Desktop: Open the app, it should show your peer ID and connected nodes.

![image](https://github.com/user-attachments/assets/688a0db2-e3f0-4445-8899-ffc3f45fb8bd)

# FILE UPLOADING
- I clicked on the file selection in IPFS desktop.

- Then i selected the option "import" and uploaded a pdf file and audio and a admit card file and also a image.

- Once the file was uploaded, IPFS generate a unique CID(content indentifier) for the file

- ![image](https://github.com/user-attachments/assets/c65b12ba-f66f-49d1-bab6-d78204aa2789)
  # ENCRYPTION AND PRIVACY ON IPFS
  1 1.	echo "Hello, IPFS!" > myfile.txt
2.	ipfs add myfile.txt
3.	openssl enc -aes-256-cbc -pbkdf2 -iter 100000 -salt -in myfile.txt -out myfile_encrypted.txt -pass pass:yourpassword
4.	ipfs add myfile_encrypted.txt
5.	cat myfile_encrypted.txt
6.	openssl enc -d -aes-256-cbc -pbkdf2 -iter 100000 -in myfile_encrypted.txt -out decrypted_file.txt -pass pass:yourpassword
7.	cat decrypted_file.txt
8.	ipfs add decrypted_file.txt
  ![image](https://github.com/user-attachments/assets/4fe63599-43eb-4003-991b-113f0e6df694)

![Screenshot 2025-04-25 045136](https://github.com/user-attachments/assets/8d7c9d98-2619-4fc0-b77b-c00fcba22351)


- # METAMASK WALLET AND TRANSACTION
- #Getting sepolia ETH from Faucet
1.Visited the google cloud Sepolia Faucet.

2.Logged in with my google account.

3.Entered my Metamask wallet address.

4.Clicked on "Request 0.02 ETH".

5.ETH was sent to my wallet within a few seconds.

6.Verified the transaction on sepolia Etherscan

![image](https://github.com/user-attachments/assets/506f06ca-9d47-493d-9855-b556cd01af5a)
#
1.Connected Metamask to Sepolia Testnet.

2.Claimed Sepolia ETH from faucet.

3.Sent ETH to another Address.

4.Verified transaction was confirmed

![WhatsApp Image 2025-04-18 at 15 33 22_d09aa71c](https://github.com/user-attachments/assets/b6c8a469-759d-4eb6-a5ab-8ddc128fbdc4)

![WhatsApp Image 2025-04-18 at 15 33 23_990e8e9a](https://github.com/user-attachments/assets/5c6b2c6a-8436-4893-b4d3-c87e98ebc749)

#TRANSACTION USING METAMASK TO ANOTHER METAMASK ACCOUNT

![WhatsApp Image 2025-04-10 at 19 43 30_c6a01dae](https://github.com/user-attachments/assets/567ad6fc-826e-4ceb-b4f2-fb9503e28029)

#HYPERLEDGER FABRIC PRACTICAL
 - installing golang-

sudo apt install golang-go

Installs Golang, which is necessary for running Hyperledger Fabric binaries.

![image](https://github.com/user-attachments/assets/1d64053f-fb91-4986-84a0-3e864e22bf79)

- Check Docker version docker --version Verifies that Docker is installed and running correctly.

- ![image](https://github.com/user-attachments/assets/cd06de67-0e1e-478a-8fe9-fee5cd74af70)

- Check Docker compose version docker -compose  --version Verifies the installation of Docker Compose.

- ![image](https://github.com/user-attachments/assets/92bc9fd9-57ee-4de9-8962-3e9b3202b495)

- List Files in current dictionary is  Shows the list of files and folders in the current directory.

![image](https://github.com/user-attachments/assets/29e5371b-2520-49cc-8adf-97ac20c168aa)

-Clone the Fabric Samples Repository and Move into the Cloned Folder
 git clone -b main https://github.com/hyperledger/fabric-samples.git

 ![image](https://github.com/user-attachments/assets/da1098c8-d18a-4e9e-bcb9-6290c898cfa2)
 - Download Fabric Binaries   curl -sSL https://bit.ly/2ysbOFE | bash -s
Downloads necessary Fabric binaries and Docker images like peer, orderer, and cryptogen.

![image](https://github.com/user-attachments/assets/f2fcd25d-13bd-4b34-b736-76fa82a03916)

![image](https://github.com/user-attachments/assets/d9a460a3-4caf-43f6-93a0-803dbfa282bc)
- .Enter the Test Network Directory

cd test-network Navigates to the directory that contains scripts for running a sample Fabric network.

![image](https://github.com/user-attachments/assets/514cdeca-bc8c-4962-864f-88aefcd1f5e3)


- View the Network Script ./network.sh Shows the options available with the network.sh script.

- Start the Fabric Network ./network.sh up Starts the network by launching peer, orderer, and CA containers, and generates the required cryptographic materials.
10.Create a Channel ./network.sh createChannel Creates a default channel (usually named mychannel) and joins the peers to it.


![image](https://github.com/user-attachments/assets/82e65079-6ff9-40e9-8280-8fa5d6214b84)


![image](https://github.com/user-attachments/assets/2ef6ab08-6bd0-4143-8ccc-95e3de627662)


- Shut Down the Network ./network.sh down Stops all containers and deletes the crypto material and artifacts created during the setup.

- ![image](https://github.com/user-attachments/assets/23c3f843-1ef1-4c3f-adeb-c2e908bfef7e)


#practical sec-
 - Q1- Create a voting system with multiple candidates. Each address can vote only once.

CODE WITH DEPLOYMENT-

![Screenshot 2025-05-19 214836](https://github.com/user-attachments/assets/98aec98c-7607-464a-a364-3adbdd6c376d)

-GIVING VOTE-
![Screenshot 2025-05-19 215959](https://github.com/user-attachments/assets/1ceda69c-af37-47ba-9d54-86066cd65d80)

- AFTER VOTING
- ![Screenshot 2025-05-19 220318](https://github.com/user-attachments/assets/415540b5-8c83-46db-868b-6ce99355db81)

- Q2- Write a contract that manages a list of student records (name, roll number). Allow adding and retrieving student data.

- CODE WITH DEPLOYMENT
 pragma solidity ^0.8.0;

contract StudentRecords {
    struct Student {
        string name;
        uint rollNumber;
    }

   Student[] public students;

   function addStudent(string memory name, uint rollNumber) public {
        students.push(Student(name, rollNumber));
    }

  function getStudent(uint index) public view returns (string memory, uint) {
        require(index < students.length, "Invalid index");
        Student memory s = students[index];
        return (s.name, s.rollNumber);
    }

  function getAllStudents() public view returns (Student[] memory) {
        return students;
    }
}
- ![image](https://github.com/user-attachments/assets/aa98dfaa-7982-41fe-903c-0c987430cdc9)
- adding student

- ![image](https://github.com/user-attachments/assets/d339963e-7568-43d0-97b3-91b127e59497)

- getting student detal
- ![image](https://github.com/user-attachments/assets/56ca92da-eadf-4be5-968d-dee9e8e64357)

- Q3- Develop a contract that only allows the deployer (owner) to call a specific function (use modifiers).

- CODE AND DEPLOYMENT-

pragma solidity ^0.8.0;

contract OwnerOnly {
    address public owner;

   constructor() {
        owner = msg.sender;
    }

   modifier onlyOwner() {
        require(msg.sender == owner, "Not owner");
        _;
    }

   function sensitiveFunction() public onlyOwner {
        // owner-only logic
    }
}

<img width="956" alt="image" src="https://github.com/user-attachments/assets/5296a7db-7c48-4718-8e42-76444aac32d6" />

![image](https://github.com/user-attachments/assets/18c7f7a4-51ec-43fb-a9e5-1e0d4c22641d)

-Q4- Write a contract where people can donate Ether and the top 3 donors are tracked.
-CODE WITH DEPLOY-

pragma solidity ^0.8.0;

contract TopDonors {
    struct Donor {
        address addr;
        uint amount;
    }
    Donor[3] public topDonors;
 function donate() public payable {
        require(msg.value > 0, "Donation must be greater than 0");
       for (uint i = 0; i < 3; i++) {
            if (msg.value > topDonors[i].amount) {
                for (uint j = 2; j > i; j--) {
                    topDonors[j] = topDonors[j - 1];
                }
                topDonors[i] = Donor(msg.sender, msg.value);
                break;
            }
        }
    }

  function getTopDonors() public view returns (Donor[3] memory) {
        return topDonors;
    }
}

<img width="959" alt="image" src="https://github.com/user-attachments/assets/78e03eed-4e88-43ab-ba46-33a75d2a3ff5" />

-Q5 - Implement a simple auction system where users can place bids, and the highest bidder wins.

-CODE WITH DEPLOYMENT

pragma solidity ^0.8.0;

contract SimpleAuction {
    address public highestBidder;
    uint public highestBid;

   mapping(address => uint) public pendingReturns;

  function bid() public payable {
        require(msg.value > highestBid, "Bid not high enough");
  if (highestBid > 0) {
            pendingReturns[highestBidder] += highestBid;
        }
  highestBidder = msg.sender;
       highestBid = msg.value;
    }

  function withdraw() public {
        uint amount = pendingReturns[msg.sender];
        require(amount > 0, "Nothing to withdraw");

   pendingReturns[msg.sender] = 0;
        payable(msg.sender).transfer(amount);
    }

   function getHighestBid() public view returns (address, uint) {
        return (highestBidder, highestBid);
    }
}

![image](https://github.com/user-attachments/assets/f075d1c7-49da-4ed2-b537-d80eb5aa7a1a)

![image](https://github.com/user-attachments/assets/81efc241-875c-4b31-86ec-281c2e7ceb84)


-Q6 -Create a contract that splits incoming Ether between 3 fixed addresses.
- CODE WITH DEPLOYMENT-
  
pragma solidity ^0.8.0;

contract Splitter {
    address payable public addr1;
    address payable public addr2;
    address payable public addr3;

   constructor(address payable _addr1, address payable _addr2, address payable _addr3) {
        addr1 = _addr1;
        addr2 = _addr2;
        addr3 = _addr3;
    }

  receive() external payable {
        uint share = msg.value / 3;
        addr1.transfer(share);
        addr2.transfer(share);
        addr3.transfer(msg.value - 2 * share); // send remainder to last
    }
}


<img width="959" alt="image" src="https://github.com/user-attachments/assets/798d2dea-b745-46b8-a197-f516213da14d" />

![image](https://github.com/user-attachments/assets/8a7f7eff-34c6-4634-a3e7-a61e8c9f77c0)






