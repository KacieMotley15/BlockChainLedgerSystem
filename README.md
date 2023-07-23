# PyChain Ledger

The PyChain Ledger is a simple blockchain implementation that stores financial transaction records. It consists of Python data classes for the `Record` and `Block` structures and a Streamlit user interface for interacting with the blockchain. Follow the steps below to understand how the ledger works and how to run the application.

## Step 1: Create a Record Data Class
The `Record` data class serves as the blueprint for financial transaction records stored in the blocks of the ledger. It consists of the attributes `sender`, `receiver`, and `amount`.

## Step 2: Modify the Existing Block Data Class to Store Record Data
The `Block` data class is modified to replace the generic `data` attribute with a `record` attribute of type `Record`. Each block in the blockchain will store a `Record` object.

## Step 3: Add Relevant User Inputs to the Streamlit Interface
The Streamlit application provides input areas for the user to enter sender, receiver, and amount details for each financial record. Clicking the "Add Block" button will create a new block with the provided information and add it to the blockchain.

## Step 4: Test the PyChain Ledger by Storing Records
You can test the PyChain ledger and the user interface by running the Streamlit application and storing multiple mined blocks in the ledger. The blockchain validation process can also be tested using the Streamlit interface.

### Running the Streamlit Application
To run the Streamlit application and interact with the PyChain ledger, follow these steps:

1. Ensure you have Python 3.10 and the required dependencies installed.
2. Navigate to the project folder in the terminal or command prompt.
3. Run the Streamlit application using the following command:


4. The application will open in your default web browser.
5. Enter the sender, receiver, and amount information in the input areas, and click the "Add Block" button to store the transaction record in the blockchain.
6. You can add multiple blocks to the blockchain using the same process.
7. The application will display the PyChain ledger with the stored blocks and their information.

### Validating the Blockchain
To validate the blockchain, use the following steps:

1. In the Streamlit application, use the slider in the sidebar to adjust the block difficulty. Higher difficulty levels require more computational power for mining blocks.
2. In the sidebar, use the drop-down menu to select the block you want to inspect.
3. Click the "Validate Chain" button to check the validity of the entire blockchain.
4. The application will display whether the blockchain is valid or not.

