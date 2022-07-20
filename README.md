# Blockchain_Pychain_Ledger

You’re a fintech engineer who’s working at one of the five largest banks in the world. You were recently promoted to act as the lead developer on their decentralized finance team. Your task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.
You’ll make the following updates to the provided Python file for this assignment, which already contains the basic PyChain ledger structure that you created throughout the module:


Create a new data class named Record. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.


Modify the existing Block data class to store Record data.


Add Relevant User Inputs to the Streamlit interface.


Test the PyChain Ledger by Storing Records.

## Technologies

This project utilizes Python and its libraries for coding, VS Code as writing tool, and streamlit for user interaction.

## Execution

Program file: pychain.py

In the terminal:  run the Streamlit application using the command: `streamlit run pychain.py`.

Enter values for the sender, receiver, and amount, and then click the "Add Block" button.
Do this several times to store several blocks in the ledger.

Verify the block contents and hashes in the Streamlit drop-down menu.

Validate the entries using the "Validate" button.

![Application Interface]
