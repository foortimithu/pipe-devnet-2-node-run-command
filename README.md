# pipe-devnet-2-node-command
Node Run
# Download Pipe Network POP Binary

This command downloads the latest Pipe Network POP binary (v0.2.8):


curl -L -o pop "https://dl.pipecdn.app/v0.2.8/pop"










chmod +x pop

# Create a Directory for Download Cache

This guide explains how to create a directory named download_cache.

## Command to Create the Directory

Run the following command:


mkdir download_cache




# Sign Up Using Pipe Network POP

This guide explains how to sign up using a referral route with the pop command.

## Sign-Up Command

Run the following command to sign up:


./pop --signup-by-referral-route 13c6ea36c249b4a9




# 🚀 Start the Pipe Network Node

This guide explains how to start the Pipe Network node with specific configurations.

## 🛠 Start Node Command

Run the following command to start the node:


sudo ./pop --ram 8 --max-disk 500 --cache-dir /data --pubKey "sol adreess"  --enable-80-443




🔴 Don't Forget to Change the Ram , Disk & PubKey with your actual values!

🪐 And Also, Don't forget to remove  the "sol address"



# 📄 Save the Node Info (⚠ Very Important!)

This step is crucial for storing your node information.  

## 💾 Save the File  

Run the following command to open the file in the nano text editor:  


nano ~/node_info.json



# Node Status & node points

To check the status of your node, run the following command:



./pop --status


./pop --points




# Guide To Upgrade v0.2.8

To upgrade to v0.2.8, follow these steps:

1. Download the new Pop binary using the following command:

curl -L -o pop "https://dl.pipecdn.app/v0.2.8/pop"


2. After downloading, make sure to set the correct permissions and move the binary to your desired directory.

chmod +x pop




























Check Points & Status From Dashboard -: https://dashboard.pipenetwork.com/node-lookup

Join TG for more Updates: https://t.me/cryptoincomefree

Thank you All
