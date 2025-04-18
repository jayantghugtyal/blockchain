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




