# Decentralized Identity Management System

## Background
I worked on this project as part of my Blockchain and Cryptocurrency course. The primary goal was to complete the project, rather than creating a professional or final product.

This project presents a client-server based, Python-implemented identity management system leveraging blockchain technology. Through a client application, individuals can register their personal information and a photograph on the blockchain, ensuring secure and tamper-proof data storage. Authorized users can retrieve verifiable information about a registered individual by submitting their photograph through the client, which sends the request to the server. The server then employs secure photo recognition to verify the user's identity before granting access to authorized information. This system empowers users with data control while utilizing blockchain for decentralized storage and enhanced security. Importantly, opting for a photo-based approach instead of facial recognition addresses ethical concerns surrounding potential misuse and bias in facial recognition technology. Continuous security improvement remains crucial for responsible development

## Prerequisites

### 1. Install MultiChain:
#### Windows:
#### Setting up MultiChain on Windows

1. **Download MultiChain:**
   - MultiChain for Windows

2. **Extraction and Configuration Options:**
   - a. Extract the individual files (e.g., `multichain-util`) directly to the `C:/` directory. This approach allows access to MultiChain tools only from the command prompt (`cmd`) when located in the `C:/` directory.
   - b. Alternatively, extract the contents to a folder of your choice. Add that folder to the system's environment variables to enable access to MultiChain tools from any folder in the command prompt (`cmd`).

Choose the option that best suits your preferences or requirements. If you have any questions about specific steps, feel free to ask!

#### Linux:
```bash
su
cd /tmp
wget https://www.multichain.com/download/multichain-2.3.3.tar.gz
tar -xvzf multichain-2.3.3.tar.gz
cd multichain-2.3.3
mv multichaind multichain-cli multichain-util /usr/local/bin # To make them easily accessible on the command line
exit # Return to your regular user
```


## 2: Launching the MultiChain Blockchain

### 2.1: Create ID Chain
```bash
  multichain-util create IDChain
```

## 2.2: Run ID Chain
```bash
  multichain IDChain -daemon
```

## 2.3 create stream
```bash
  multichain-cli IDChain create stream identity_stream true
  multichain-cli IDChain subscribe identity_stream
```

## 2.4: Replace IP Adresses in your client script with appropriate Server IP Address

## Working
## Input

1. Execute the server-input script.
2. Run the client-input script.
3. Enter the required information and the correct location for the person's picture. Ensure the picture is clear and front-facing.

## Retrieve Information Workflow

1. **Run the Server-Retrieve Script:**
   - Execute the server-retrieve script.

2. **Execute the Client-Retrieve Script:**
   - Run the client-retrieve script.

3. **Provide Correct Information:**
   - Input the accurate information as required.

4. **Specify Picture Location:**
   - Provide the location of the new picture to ensure a match.


