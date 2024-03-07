# Decentralized-Identity-Management-System


## Background
I worked on this as part of my Blockchain and Cryptocurrency course project for the semester. The goal was simply to complete the project and not for professional or final project purposes.

## Pre-requisites

### 1: Install multichain:
#### Windows:
## Setting up MultiChain on Windows

1. **Download MultiChain:**
   - [MultiChain for Windows](https://www.multichain.com/download/multichain-windows-2.3.3.zip)

2. **Extraction and Configuration Options:**
   - a. Extract the individual files (e.g., multichain-util) directly to the C:/ directory. This involves copying these files directly into the C:/ directory, allowing access to MultiChain tools only from the command prompt (cmd) when located in the C:/ directory.
   - b. Alternatively, extract the contents to a folder of your choice. Add that folder to the system's environment variables to enable access to MultiChain tools from any folder in the command prompt (cmd).

Choose the option that best fits your preferences or requirements. If you have questions about a specific step, feel free to inquire!

#### Linux:
	su
	cd /tmp
	wget https://www.multichain.com/download/multichain-2.3.3.tar.gz
	tar -xvzf multichain-2.3.3.tar.gz\
	cd multichain-2.3.3\
	mv multichaind multichain-cli multichain-util /usr/local/bin #to make easily accessible on the command line
	exit #to return to your regular user

## 2: Launching the MultiChain Blockchain

### 2.1: Create ID Chain

```bash
multichain-util create IDChain '''


2.2: Run ID chain

    multichain IDChain -daemon

2.3 create stream

  multichain-cli IDChain create stream identity_stream true
  multichain-cli IDChain subscribe identity_stream

2.4: Replace IP Adresses in your client script with appropriate Server IP Address

## Working
### Input
Execute the server-input script.
Run the client-input script.
Enter the required information and the correct location for the person's picture. Ensure the picture is clear and front-facing.
### Retrieve info
## Retrieve Information Workflow

1. **Run the Server-Retrieve Script:**
   Execute the server-retrieve script.

2. **Execute the Client-Retrieve Script:**
   Run the client-retrieve script.

3. **Provide Correct Information:**
   Input the accurate information as required.

4. **Specify Picture Location:**
   Provide the location of the new picture to ensure a match with the person retrieving information.


