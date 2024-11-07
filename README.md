Explanation:
Backend (app.py):

Web3.py connects to an Ethereum blockchain.
A simple Flask app is set up to handle voting and retrieving vote counts via a smart contract on the blockchain.
The vote route handles submitting a vote transaction, while the get_votes route retrieves the vote count for each candidate.
Frontend (index.html):

Simple HTML interface with buttons for voting for candidates.
JavaScript is used to send requests to the backend to cast votes and fetch the vote count.
Running the Application:
Make sure an Ethereum node is running (e.g., Ganache for local development).

Deploy the smart contract for voting on the Ethereum blockchain (you can use a simple contract written in Solidity for this).

Start the Flask app by running:

Open the browser and navigate to http://127.0.0.1:5000/ to access the voting page.
